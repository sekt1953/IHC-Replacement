# Installations dokumentation

## Home Assistant & ESPHome

* Home Assistant & ESPHome instllation
  * [Input - LK taster, Pir & Røgdetector's kabling](./LK_taster_Pir_Røgdetectors_kabling.md#input)
  * [Output - LK taster, Pir & Røgdetector's kabling](./LK_taster_Pir_Røgdetectors_kabling.md#output)
* [IHC (gammel installation)](./IHC_gammel%20installation.md)

<<<<<<< HEAD
|Kabel|Lokalitet|Placering____*******|Komponent|Terminal|Farve|I/O Interface|I2C-Addr||||
|:---:|:---|:---|:---|:---:|:---|:---|:---|:---|:---|:---|
|1|Lille Bad|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_00|0x23.0||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_01|0x23.1||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_02|0x23.2||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_03|0x23.3||
||||||||||
|2|Kontor|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_04|0x23.4||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_05|0x23.5||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_06|0x23.6||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_07|0x23.7||
||||||||||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_08|0x23.8||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_09|0x23.9||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_10|0x23.10||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_11|0x23.11||
||||||||||
|9|Soveværelse|Ved seng V|Tryk 4 tast|GND|Blå|GND|||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk ØV|Sort|Input_12|0x23.12||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk ØH|Grøn|Input_13|0x23.13||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk NV|Violet|Input_14|0x23.14||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk NH|Brun|Input_15|0x23.15||
||||||||||
||||||||||
|4|Garage|Ved bryggers dør|Tryk 6 tast|GND|Blå|GND|||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk ØV|Sort|Input_16|0x24.0||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk ØH|Grøn|Input_17|0x24.1||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk MV|Violet|Input_18|0x24.2||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk MH|Brun|Input_19|0x24.3||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk NV|Rød|Input_20|0x24.4||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk NH|Grå|Input_21|0x24.5||
||||||||||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|GND|Blå|GND|||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk ØV|Sort|Input_22|0x24.6||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk ØH|Grøn|Input_23|0x24.7||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk MV|Violet|Input_24|0x24.8||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk MH|Brun|Input_25|0x24.9||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk NV|Rød|Input_26|0x24.10||
|5|Køkken|Ved bryggers dør|Tryk 6 tast|Tryk NH|Grå|Input_27|0x24.11||
||||||||||
||||||||||
|6|Stue|På væg|Tryk 6 tast|GND|Blå|GND|||
|6|Stue|På væg|Tryk 6 tast|Tryk ØV|Sort|Input_32|0x25.0||
|6|Stue|På væg|Tryk 6 tast|Tryk ØH|Grøn|Input_33|0x25.1||
|6|Stue|På væg|Tryk 6 tast|Tryk MV|Violet|Input_34|0x25.2||
|6|Stue|På væg|Tryk 6 tast|Tryk MH|Brun|Input_35|0x25.3||
|6|Stue|På væg|Tryk 6 tast|Tryk NV|Rød|Input_36|0x25.4||
|6|Stue|På væg|Tryk 6 tast|Tryk NH|Grå|Input_37|0x25.5||
||||||||||
|7|Entré|Ved dør til køkken|Tryk 6 tast|GND|Blå|GND|||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk ØV|Sort|Input_38|0x25.6||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk ØH|Grøn|Input_39|0x25.7||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk MV|Violet|Input_40|0x25.8||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk MH|Brun|Input_41|0x25.9||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk NV|Rød|Input_42|0x25.10||
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk NH|Grå|Input_43|0x25.11||
||||||||||
|10|Entré|Ved yderdør|Tryk 4 tast|GND|Blå|GND|||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk ØV|Sort|Input_44|0x25.12||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk ØH|Grøn|Input_45|0x25.13||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk NV|Violet|Input_46|0x25.14||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk NH|Brun|Input_47|0x25.15||
||||||||||
||||||||||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|GND|Blå|GND|||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk ØV|Sort|Input_48|0x26.0||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk ØH|Grøn|Input_49|0x26.1||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk MV|Violet|Input_50|0x26.2||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk MH|Brun|Input_51|0x26.3||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk NV|Rød|Input_52|0x26.4||
|8|Soveværelse|Ved dør til st. bad|Tryk 6 tast|Tryk NH|Grå|Input_53|0x26.5||
||||||||||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|GND|Blå|GND|||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk ØV|Sort|Input_54|0x26.6||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk ØH|Grøn|Input_55|0x26.7||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk MV||Input_56|0x26.8||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk MH||Input_57|0x26.9||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk NV|Rød|Input_58|0x26.10||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk NH|Grå|Input_59|0x26.11||
||||||||||
||PIR||Pir|GND||GND|||
|33|Stue|På væg|Pir|Alarm|Sort|Input_60|0x26.12||
|32|Soveværelse|Ved dør til toilet|Pir|Alarm|Hvid|Input_61|0x26.13||
|31|Bryggers|På væg|Pir|Alarm|Sort|Input_62|0x26.14||
|30|Garage|På væg|Pir|Alarm|Sort|Input_63|0x26.15||
||||||||||
||||||||||
|12|Garage|Ved yderdør|Tryk 6 tast|GND|Blå|GND|||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk ØV|Sort|Input_64|0x27.0||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk ØH|Grøn|Input_65|0x27.1||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk MV|Violet|Input_66|0x27.2||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk MH||Input_67|0x27.3||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk NV|Rød|Input_68|0x27.4||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk NH||Input_69|0x27.5||
||||||||||
||||||||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|GND|Grå|GND|||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk ØV|Rød|Input_76|0x27.12|||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk ØH|Hvid|Input_77|0x27.13|||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk NV|Orange|Input_78|0x27.14|||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk NH|Gul|Input_7931|0x27.15||
=======
## Tailscale
>>>>>>> 37d341f (doc opdelt i nye og gammel)

* Videoer
  * [Remotely access and share your self-hosted services](https://youtu.be/Vt4PDUXB_fg "Tailscale")
