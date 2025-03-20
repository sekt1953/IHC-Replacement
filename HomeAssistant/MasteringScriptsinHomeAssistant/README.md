# Mastering Scripts in Home Assistant

## Kilder:

* [Smart Home Junkie](https://www.youtube.com/@SmartHomeJunkie)
  * [Mastering Scripts in Home Assistant: A Comprehensive Guide](https://youtu.be/vD_xckjQxRk)
* [SlackerLabs](https://www.youtube.com/@SlackerLabs)
  * [Mastering Home Assistant Templates: Intro to Date and Time](https://youtu.be/2WIi5xq0iHI?list=PLJAP47iycH2IV8m5RnMF4hmZ_mVb7vgv_)

## Use Case 1: Send a fixed message to your phone

## Use Case 2: [Send a custom message to your phone using fields in scripts](https://www.youtube.com/watch?v=vD_xckjQxRk&t=219s)

* Script: "Notify: Persistent"

```code
sequence:
  - action: persistent_notification.create
    metadata: {}
    data:
      message: "{{message}}"
      title: "{{title}}"
alias: "Notify: Persistent"
description: 
fields:
  title:
    selector:
      text: null
    name: title
    description: Enter a title for your notification
    required: true
  message:
    selector:
      text: null
    name: message
    description: Enter a message for your notification
    required: true
```

* Automation: "Notify: Send a custom message"

```code
alias: "Notify: Send a custom message"
description: ""
triggers:
  - trigger: state
    entity_id:
      - binary_sensor.ihc1_input_00
      - binary_sensor.ihc1_input_02
    to: "on"
conditions: []
actions:
  - action: script.notify_persistent
    data:
      title: This is a custom title
      message: and this is the custom message
mode: single

```

## Use Case 3: [Send a custom weather condition to your phone using response variables in scripts](https://www.youtube.com/watch?v=vD_xckjQxRk&t=454s)

* Script: "Weather: get custom weather condition"

```code
alias: "Weather: get custom weather condition"
variables:
  weather_condition: |
    {% set temperature = state_attr("weather.forecast_hjem","temperature") %}
    {% if (temperature < 5) %}
      {% set condition = "Cold" %}
    {% elif (temperature >= 5 and temperature <= 15 ) %}
      {% set condition = "Chilly" %}
    {% elif (temperature >= 15 and temperature <= 20 ) %}
      {% set condition = "Comfortable" %}
    {% elif (temperature >= 20 and temperature <= 30 ) %}
      {% set condition = "Warm" %}
    {% elif (temperature >= 30 ) %}
      {% set condition = "To Warm !!" %}
    {% endif %}
    {{ {'value': condition} }}
sequence:
  - stop: End
    response_variable: weather_condition
description: ""
```

* Automation: ""

```code
alias: "Notify: Send a custom message"
description: ""
triggers:
  - trigger: state
    entity_id:
      - binary_sensor.ihc1_input_00
      - binary_sensor.ihc1_input_02
      - switch.ihc1_output_00
    to: "on"
    for:
      hours: 0
      minutes: 0
      seconds: 1
conditions: []
actions:
  - action: script.weather_get_custom_weather_condition
    data: {}
    response_variable: result
  - action: script.notify_persistent
    data:
      message: The weather is {{ result.value }}
      title: Weather Condition
mode: single

```

## Mastering Home Assistant Templates: Intro to Date and Time

[Mastering Home Assistant Templates: Intro to Date and Time](https://www.youtube.com/watch?v=2WIi5xq0iHI&list=PLJAP47iycH2IV8m5RnMF4hmZ_mVb7vgv_&index=3&t=1707s)

```code
{{ states.switch.ihc1_output_00.last_updated }}
{{ states.switch.ihc1_output_00.last_changed }}

{{ as_datetime('2024-03-20 12:04:20') }}
{{ as_timestamp('2024-03-20 12:04:20') }}
{{ as_timestamp('2024-03-20') }}

**
{{ 
  as_timestamp(now()) -
  as_timestamp(states.switch.ihc1_output_00.last_changed)
}}
```
