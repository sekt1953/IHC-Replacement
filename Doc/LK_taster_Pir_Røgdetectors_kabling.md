# LK taster, Pir & Røgdetector's kabling

## Input

|Kabel|Lokalitet|Placering____*******|Komponent|Terminal|Farve|I/O Interface|I2C-Addr|Kort_Tryk|Langt_Tryk||
|:---:|:---|:---|:---|:---:|:---|:---|:---|:---|:---|:---|
|1|Lille Bad|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_00|0x23.0|Output_34|Output_34||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_01|0x23.1|Output_05|||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_02|0x23.2|Output_32|||
|1|Lille Bad|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_03|0x23.3|Output_06|||
||||||||||
|2|Kontor|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_04|0x23.4|Output_26|Output_26||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_05|0x23.5||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_06|0x23.6||
|2|Kontor|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_07|0x23.7||
||||||||||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|GND|Blå|GND|||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk ØV|Sort|Input_08|0x23.8|Output_27|Output_27||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk ØH|Grøn|Input_09|0x23.9||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk NV|Violet|Input_10|0x23.10||
|3|Gæsteværelse|Ved dør|Tryk 4 tast|Tryk NH|Brun|Input_11|0x23.11||
||||||||||
|9|Soveværelse|Ved seng V|Tryk 4 tast|GND|Blå|GND|||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk ØV|Sort|Input_12|0x23.12||||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk ØH|Grøn|Input_13|0x23.13|Output_12|||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk NV|Violet|Input_14|0x23.14|Output_17|||
|9|Soveværelse|Ved seng V|Tryk 4 tast|Tryk NH|Brun|Input_15|0x23.15||||
||||||||||
||||||||||
|4|Garage|Ved bryggers dør|Tryk 6 tast|GND|Blå|GND|||||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk ØV|Sort|Input_16|0x24.0||||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk ØH|Grøn|Input_17|0x24.1||||
|4|Garage|Ved bryggers dør|Tryk 6 tast|Tryk MV|Violet|Input_18|0x24.2||||
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
|7|Entré|Ved dør til køkken|Tryk 6 tast|Tryk NH||Input_43|0x25.11||
||||||||||
|10|Entré|Ved yderdør|Tryk 4 tast|GND|Blå|GND|||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk ØV|Sort|Input_44|0x25.12||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk ØH|Grøn|Input_45|0x25.13||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk NV|Violet|Input_46|0x25.14||
|10|Entré|Ved yderdør|Tryk 4 tast|Tryk NH||Input_47|0x25.15||
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
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk MV|Violet|Input_56|0x26.8||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk MH|Brun|Input_57|0x26.9||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk NV|Rød|Input_58|0x26.10||
|11|Køkken|Ved dør til viktualrum|Tryk 6 tast|Tryk NH|Grå|Input_59|0x26.11||
||||||||||
|33|Stue|På væg|Pir|Alarm|Sort|Input_60|0x26.12||
||Soveværelse|Ved dør til toilet|Pir|Alarm|Hvid|Input_61|0x26.13||
|31|Bryggers|På væg|Pir|Alarm|Sort|Input_62|0x26.14||
|30|Garage|På væg|Pir|Alarm|Sort|Input_63|0x26.15||
||||||||||
||||||||||
|12|Garage|Ved yderdør|Tryk 6 tast|GND|Blå|GND|||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk ØV|Sort|Input_64|0x27.0||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk ØH|Grøn|Input_65|0x27.1||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk MV|Violet|Input_66|0x27.2||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk MH|Brun|Input_67|0x27.3||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk NV|Rød|Input_68|0x27.4||
|12|Garage|Ved yderdør|Tryk 6 tast|Tryk NH|Grå|Input_69|0x27.5||
||||||||||
||Stue||Røgsensor||Orange|Input_70|0x27.6|
||Soveværelse||Røgsensor||Hvid|Input_71|0x27.7||
|36|Bryggers|I loft|Røgsensor||Sort|Input_72|0x27.8|Udgang 7|02|Violet|
||Garage||Røgsensor|||Input_73|0x27.9||Udgang 7|02||
||Udendørs|Indkørsel|Røgsensor||Grøn|Input_74|0x27.10|Udgang 7|03|HvidBlå|
||||||||||||
||||||||||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|GND|Grå|GND|||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk ØV|Rød|Input_76|0x27.12||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk ØH|Hvid|Input_77|0x27.13||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk NV|Orange|Input_78|0x27.14||||
|9|Soveværelse|Ved seng H|Tryk 4 tast|Tryk NH|Gul|Input_79|0x27.15||||
||||||||||||

## Output

### Relæ 220VAC

||Lokalitet|Placering|Relæ||||IHC Modul|I/O Interface|I2C-Addr|
|---:|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|0|Køkken|Spisebord|||||IHC1|Output_00|0x20.0|
|1|||||||IHC1|Output_01|0x20.1|
|2|Udelys|Hæk|||||IHC1|Output_02|0x20.2|
|3|Køkken|Spot|||||IHC1|Output_03|0x20.3|
|4|Stue|Spot|||||IHC1|Output_04|0x20.4|
|5|LilleBad|Spot|||||IHC1|Output_05|0x20.5|
|6|Bryggers|Spot|||||IHC1|Output_06|0x20.6|
|7|Stort Bad|Spot|||||IHC1|Output_07|0x20.7|
|8|||||||IHC1|Output_08|0x20.8|
|9|||||||IHC1|Output_09|0x20.9|
|10|Udelys||||||IHC1|Output_10|0x20.10|
|11|||||||IHC1|Output_11|0x20.11|
|12|Stort Bad|Spejl|||||IHC1|Output_12|0x20.12|
|13|||||||IHC1|Output_13|0x20.13|
|14|||||||IHC1|Output_14|0x20.14|
|15|||||||IHC1|Output_15|0x20.15|
|16|Soveværelse|Loft|||||IHC1|Output_16|0x21.0|
|17|WalkIn|Loft|||||IHC1|Output_17|0x21.1|
|18|Entre||||||IHC1|Output_18|0x21.2|
|19|Stue|Sofabord|||||IHC1|Output_19|0x21.3|
|20|Køkken|Bord|||||IHC1|Output_20|0x21.4|
|21|||||||IHC1|Output_21|0x21.5|
|22|||||||IHC1|Output_22|0x21.6|
|23|||||||IHC1|Output_23|0x21.7|
|24|||||||IHC1|Output_24|0x21.8|
|25|Garage|Nord|||||IHC1|Output_25|0x21.9|
|26|Kontor|Loft|||||IHC1|Output_26|0x21.10|
|27|Værelse|Loft|||||IHC1|Output_27|0x21.11|
|28|Garage|Syd|||||IHC1|Output_28|0x21.12|
|29|||||||IHC1|Output_29|0x21.13|
|30||Stikkontakt|||||IHC1|Output_30|0x21.14|
|31|||||||IHC1|Output_31|0x21.15|
|32|Bryggers|Bord|||||IHC1|Output_32|0x22.0|
|33|Spisekammer|loft|||||IHC1|Output_33|0x22.1|
|34|Lille Bad|Spejl|||||IHC1|Output_34|0x22.2|
|35|||||||IHC1|Output_35|0x22.3|
|36|||||||IHC1|Output_36|0x22.4|
|37|||||||IHC1|Output_37|0x22.5|
|38|||||||IHC1|Output_38|0x22.6|
|39|||||||IHC1|Output_39|0x22.7|
|40|||||||IHC1|Output_40|0x22.8|
|41|||||||IHC1|Output_41|0x22.9|
|42|||||||IHC1|Output_42|0x22.10|
|43|||||||IHC1|Output_43|0x22.11|
|44|||||||IHC1|Output_44|0x22.12|
|45|||||||IHC1|Output_45|0x22.13|
|46|||||||IHC1|Output_46|0x22.14|
|47|||||||IHC1|Output_47|0x22.15|

### Gammel installation

||Lokalitet|Placering|Komponent|Farve|Kabel|Kabeltype|IHC Modul|Adresse|Ledning|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|0|Stue|Spot|Lampeudtag|--|208|2x4+2x1.5|Udgang 8|04|Sort|
|1|Stue|I loft|Lampeudtag|Hvid|211|5x1.5|Udgang 4|05|Hvid|
|2|Stue|I kip|Lampeudtag|Sort|205|5x1.5|Udgang 4|02|Sort|
|3|Stue|TV|Lampeudtag|Hvid|205|5x1.5|Udgang 4|03|Hvid|
|4|Stue|Gulv|Stikkontakt|Brun|103|5x1.5|Udgang 1|07|Brun|
|||||||||||
|5|Entré|I loft|Lampeudtag|Brun|206|5x1.5|Udgang 4|06|Brun|
|6|Entré|Gulv|Stikkontakt|Hvid|102|5x1.5|Udgang 2|03|Hvid|
|||||||||||
|7|Køkken|Spot|Lampeudtag|--|209|2x1.5|Udgang 8|05|Violet|
|8|Køkken|I loft|Lampeudtag|Sort|205|5x1.5|Udgang 4|04|Sort|
|9|Køkken|Over spisebord (gl. lysdæmp D12)|Lampeudtag|Brun|205|5x1.5|Udgang 8|08|Brun|
|10|Køkken|I kip D13|Lampeudtag|Brun|205|5x1.5|Udgang 6|03|Violet|
|11|Køkken|Gulv|Stikkontakt|Hvid|101 / 102|5x1.5|Udgang 1|03|Hvid|
|||||||||||
|12|Soveværelse|I loft|Lampeudtag|Hvid|206|5x1.5|Udgang 4|08|Hvid|
|13|Soveværelse|Gulv|Stikkontakt|Sort|103|5x1.5|Udgang 1|08|Sort|
|14|Soveværelse|TV|Stikkontakt|Hvid|207|5x1.5|Udgang 5|03|Hvid|
|||||||||||
|15|Værelse(8)|I loft|Lampeudtag|Sort|201|5x1.5|Udgang 3|04|Sort|
|16|Værelse(8)|Gulv|Stikkontakt|Brun|101 / 104|5x1.5|Udgang 1|04|Brun|
|||||||||||
|17|Værelse(2)|I loft|Lampeudtag|Hvid|201|5x1.5|Udgang 3|05|Hvid|
|18|Værelse(2)|Gulv|Stikkontakt|Brun|101|5x1.5|Udgang 1|01|Brun|
|||||||||||
|19|Stort Bad|I loft|Lampeudtag|Brun|207|5x1.5|Udgang 5|01|Brun|
|20|Stort Bad|Spot|Lampeudtag|--|210|2x4+2x1.5|Udgang 8|01|Brun|
|21|Stort Bad|Gulv|Stikkontakt|Sort|207|5x1.5|Udgang 5|02|Sort|
|||||||||||
|22|Bryggers|Spot|Lampeudtag|--|202|2x1.5|Udgang 8|02|Brun|
|23|Bryggers|På væg|Lampeudtag|Hvid|204|5x1.5|Udgang 2|07|Hvid|
|24|Bryggers|Gulv|Stikkontakt|Sort|101 / 204|5x1.5|Udgang 1|02|Sort|
|||||||||||
|25|Lille Bad|Spot|Lampeudtag|--|203|2x1.5|Udgang 8|03|Brun|
|26|Lille Bad|På væg|Lampeudtag|Brun|107|5x1.5|Udgang 2|04|Brun|
|27|Lille Bad|Gulv|Stikkontakt|Sort|107|5x1.5|Udgang 2|05|Sort|
|||||||||||
|28|Garage|I loft|Lampeudtag|Sort|200|5x1.5|Udgang 3|06|Sort|
|29|Garage|I loft|Lampeudtag|Hvid|200|5x1.5|Udgang 3|07|Hvid|
|30|Garage|I loft Ex|Lampeudtag|Brun|201|5x1.5|Udgang 3|03|Brun|
|31|Garage|Gulv|Stikkontakt|Hvid|100|5x1.5|Udgang 1|06|Hvid|
|32|Garage|Gulv Ex|Stikkontakt|Sort|100|5x1.5|Udgang 1|05|Sort|
|||||||||||
|33|Viktualrum|I loft|Lampeudtag|Brun|204|5x1.5|Udgang 2|06|Brun|
|34|Viktualrum|Gulv|Stikkontakt|Brun|102|5x1.5|Udgang 2|02|Brun|
|||||||||||
|35|Walkin|I loft|Lampeudtag|Sort|206|5x1.5|Udgang 4|07|Sort|
|36|Walkin|Gulv|Stikkontakt|Hvid|103|5x1.5|Udgang 2|01|Hvid|
|37|Walkin|Medie Center|Stikkontakt|Sort|213|5x1.5|Udgang 2|08|Sort|
|||||||||||
|38|Udendørs|På væg udv|Lampeudtag|Brun|212|3x1.5|Udgang 5|04|Brun|
|39|Udendørs|Spot|Lampeudtag|Hvid|107|5x1.5|Udgang 5|06|Hvid|
|40|Udendørs|Stikk ter.|Stikkontakt|Brun|105|5x1.5|Udgang 3|01|Brun|
|41|Udendørs|Stikk gar.|Stikkontakt|Brun|106|5x1.5|Udgang 3|02|Brun|
|42|Udendørs|I Jord Udvendig|Lampeudtag|Brun|--|5x1.5|Udgang 8|06|Brun|
|||||||||||
|43|Loft|I loft|Lampeudtag|Sort|107|5x1.5|Udgang 5|05|Sort|
|44|Loft|Dobbeltstik|Stikkontakt|--|--|5x1.5|Udgang 3|08|Sort|
|||||||||||
|45|Sluk Alt|Spot køk+stue|Lampeudtag|--|--|--|Udgang 6|02|Grøn|
|46|Magnetventil|--|Magnetventil NO|--|--|--|Udgang 8|07|Brun|
|||||||||||
|47|Køkken|Ved dør til viktualrum|Lydgiver intern 80 dB|--|38|IHC LINK-10 NOPOVIC (5x2x0 6mm)|Udgang 6|05| Sort|
|48|Køkken|Ved dør til viktualrum|Lydgiver intern 102 dB|--|38|IHC LINK-10 NOPOVIC (5x2x0 6mm)|Udgang 6|06|Grøn|
|49|Soveværelse|Diode|Lampeudtag|Gul|8|IHC LINK-10 NOPOVIC (5x2x0 6mm)|Udgang 7|04|Gul|
|50|Garage|Diode|Dørlås|--|--|IHC LINK-10 NOPOVIC (5x2x0 6mm)|Udgang 7|01|Orange|
|51|Udendørs|På væg udv|Lydgiver ekstern|Sort|39|IHC LINK-10 NOPOVIC (5x2x0 6mm)|Udgang 6|04|Sort|
