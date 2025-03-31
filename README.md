# IHC-Replacement

Her laver jeg en erstatning for mit LK IHC system

Jeg kan ikke længere få reserve dele til mit IHC system som styrer alt lys i huset. 
Jeg har i forevejen et Home Assistant project igang, så nu vil jeg fremstille PCB som kan virke som interface mellem min El installation Og Home Assistant.

## Fritzing

* I/O Ver. 0.22 FritzingFab
  * ![PCB 0.22](./Fritzing/IO-PCB/FritzingFab_v_0.22/Input_Board_021_pcb.png)
  * ![schem 0.22](./Fritzing/IO-PCB/FritzingFab_v_0.22/Input_Board_021_schem.png)
  * [fzz 0.22](./Fritzing/IO-PCB/FritzingFab_v_0.22/Input_Board_022.fzz)
* I/O Ver. 0.40 
  * ![PCB 0.40](./Fritzing/IO-PCB/v_0.4.0/Input_Board_040_pcb.png )
  * ![schem 0.40](./Fritzing/IO-PCB/v_0.4.0/Input_Board_040_schem.png)
  * [Fritzing file version 0.30](./Fritzing/IO-PCB/v_0.4.0/Input_Board_040.fzz)

### Bill of Materials

* I/O-PCB IHC-Replacement v.040 20250331 16:39
  * Fælleds for Input og Output config
    * 1 stk PCB, I/O-PCB IHC-Replacement v.040
    * 2 stk MCP20017-E/SP 16-bit
    * 2 stk Ceramic Capacitor 100nF
    * 2 stk 10kΩ Resistor SMD 1206
    * 2 stk 5 pol connector for I2C bus, vinkel MOD 2,54mm
    * 4 stk 10 pol connector for Input / Output, KF141R-10P MOD 2,54mm
    * 2 stk jumper for I2C addr. settings
    * 1 stk Lodepasta 138 Deg. 30g
  * Matrialer for Input PCB
    * 64 stk 1N4148 SMD 1206
    * 32 stk 10kΩ Resistor SMD 1206
  * Matrialer for Output PCB
    * 4 stk ULN2803A
    * 2 stk 3pol connector for nødbelysning MOD 2,54mm

## FreeCAD

* [DINBox ](./FreeCAD/DINBox_002.FCStd)
  * ![Images dinbox](./FreeCAD/Images/Skærmbillede%20fra%202024-12-03%2021-47-26.png)
* [TrykHolder](./FreeCAD/TrykHolder/Trykholder_v4.FCStd)
  * ![images trykholder](./FreeCAD/TrykHolder/Images/Skærmbillede%20fra%202025-03-21%2016-08-51.png)
  * ![images insite trykholder](./FreeCAD/TrykHolder/Images/Skærmbillede%20fra%202025-03-21%2016-20-50.png)
  * [FreeCAD File for TrykHolder](./FreeCAD/TrykHolder/Trykholder_v4.FCStd)

## Home Assistant

* ![Skærmbilled](./HomeAssistant/Images/Skærmbillede%20fra%202025-03-30%2011-12-03.png)
  * [Raw configuration Finn's IHC](./HomeAssistant/RawConfigurationFinnsIHC.yaml)

## ESPHome

* [ihc1.yaml](./ESPHome/ihc1.yaml)
* Include files
  * Olimex ESP32-POE-ISO-16MB
    * [.olimex-esp32-poe.yaml](./ESPHome/Includes/ESP32/.olimex-esp32-poe.yaml)
  * MCP23017
    * [.mcp23017_ids.yaml](./ESPHome/Includes/MCP23017/.mcp23017_ids.yaml)
    * [.mcp23017_input.yaml](./ESPHome/Includes/MCP23017/.mcp23017_input.yaml)
    * [.mcp23017_output.yaml](./ESPHome/Includes/MCP23017/.mcp23017_output.yaml)
