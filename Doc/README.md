# Installations dokumentation

## Home Assistant & ESPHome instllation

### Input

#### LK taster

||Lokalitet|Placering____*****|Komponent|Kabel|Terminal|Farve|I/O Interface|||
|:---:|:---|:---|:---|:---:|:---|:---|:---|:---:|:---:|
|GND|Lille Bad|Ved dør|Tryk 4 tast|1|GND|Blå|GND|||
|0|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk ØV|Sort|Input_00|||
|1|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk ØH|Grøn|Input_01|||
|2|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk NV|Violet|Input_02|||
|3|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk NH|Brun|Input_03|||
|||||||||||
|GND|Kontor|Ved dør|Tryk 4 tast|2|GND|Blå|GND|||
|4|Kontor|Ved dør|Tryk 4 tast|2|Tryk ØV|Sort|Input_04|||
|5|Kontor|Ved dør|Tryk 4 tast|2|Tryk ØH|Grøn|Input_05|||
|6|Kontor|Ved dør|Tryk 4 tast|2|Tryk NV|Violet|Input_06|||
|7|Kontor|Ved dør|Tryk 4 tast|2|Tryk NH|Brun|Input_07|||
|||||||||||
|GND|Gæsteværelse|Ved dør|Tryk 4 tast|3|GND|Blå|GND|||
|8|Gæsteværelse|Ved dør|Tryk 4 tast|3|Tryk ØV|Sort|Input_08|||
|9|Gæsteværelse|Ved dør|Tryk 4 tast|3|Tryk ØH|Grøn|Input_09|||
|10|Gæsteværelse|Ved dør|Tryk 4 tast|3|Tryk NV|Violet|Input_10|||
|11|Gæsteværelse|Ved dør|Tryk 4 tast|3|Tryk NH|Brun|Input_11|||
|||||||||||
|||||||||||
|GND|Garage|Ved bryggers dør|Tryk 6 tast|4|GND|Blå|GND|||
|12|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk ØV|Sort|Input_16|||
|13|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk ØH|Grøn|Input_17|||
|14|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk MV||Input_18|||
|15|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk MH||Input_19|||
|16|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk NV|Rød|Input_20|||
|17|Garage|Ved bryggers dør|Tryk 6 tast|4|Tryk NH||Input_21|||
|||||||||||
|GND|Køkken|Ved bryggers dør|Tryk 6 tast|5|GND|Blå|GND|||
|18|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk ØV|Sort|Input_22|||
|19|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk ØH|Grøn|Input_23|||
|20|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk MV|Violet|Input_24|||
|21|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk MH||Input_25|||
|22|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk NV|Rød|Input_26|||
|23|Køkken|Ved bryggers dør|Tryk 6 tast|5|Tryk NH|Grå|Input_27|||
|||||||||||
|GND|Stue|På væg|Tryk 6 tast|6|GND|Blå|GND|||
|24|Stue|På væg|Tryk 6 tast|6|Tryk ØV|Sort|Input_28|||
|25|Stue|På væg|Tryk 6 tast|6|Tryk ØH|Grøn|Input_29|||
|26|Stue|På væg|Tryk 6 tast|6|Tryk MV|Violet|Input_30|||
|27|Stue|På væg|Tryk 6 tast|6|Tryk MH||Input_31|||
|28|Stue|På væg|Tryk 6 tast|6|Tryk NV|Rød|Input_32|||
|29|Stue|På væg|Tryk 6 tast|6|Tryk NH|Grå|Input_33|||
|||||||||||
|GND|Entré|Ved dør til køkken|Tryk 6 tast|7|GND|Blå|GND|||
|30|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk ØV|Sort|Input_34|||
|31|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk ØH|Grøn|Input_35|||
|32|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk MV|Violet|Input_36|||
|33|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk MH|Brun|Input_37|||
|34|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk NV|Rød|Input_38|||
|35|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk NH||Input_39|||
|||||||||||
|GND|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|GND|Blå|GND|||
|36|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk ØV|Sort|Input_40|||
|37|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk ØH|Grøn|Input_41|||
|38|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk MV|Violet|Input_42|||
|39|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk MH|Brun|Input_43|||
|40|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk NV|Rød|Input_44|||
|41|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk NH|Grå|Input_45|||
|||||||||||
|GND|Soveværelse|Ved seng V|Tryk 4 tast|9|GND|Blå|GND|||
|42|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk ØV|Sort||||
|43|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk ØH|Grøn||||
|44|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk NV|Violet||||
|45|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk NH|Brun||||
|||||||||||
|GND|Soveværelse|Ved seng H|Tryk 4 tast|9|GND|Blå|GND|||
|46|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk ØV|Rød||||
|47|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk ØH|Hvid||||
|48|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk NV|Orange||||
|49|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk NH|08|Gul|||
|||||||||||
|GND|Entré|Ved yderdør|Tryk 4 tast|10|GND|Blå|GND|||
|50|Entré|Ved yderdør|Tryk 4 tast|10|Tryk ØV|Sort||||
|51|Entré|Ved yderdør|Tryk 4 tast|10|Tryk ØH|Grøn||||
|52|Entré|Ved yderdør|Tryk 4 tast|10|Tryk NV|Violet||||
|53|Entré|Ved yderdør|Tryk 4 tast|10|Tryk NH|||||
|||||||||||
|GND|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|GND|Blå|GND|||
|54|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk ØV|Sort||||
|55|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk ØH|Grøn||||
|56|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk MV|||||
|57|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk MH|||||
|58|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk NV|Rød||||
|59|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk NH|Grå||||
|||||||||||
|GND|Garage|Ved yderdør|Tryk 6 tast|12|GND|Blå|GND|||
|60|Garage|Ved yderdør|Tryk 6 tast|12|Tryk ØV|Sort||||
|61|Garage|Ved yderdør|Tryk 6 tast|12|Tryk ØH|Grøn||||
|62|Garage|Ved yderdør|Tryk 6 tast|12|Tryk MV|Violet||||
|63|Garage|Ved yderdør|Tryk 6 tast|12|Tryk MH|||||
|64|Garage|Ved yderdør|Tryk 6 tast|12|Tryk NV|Rød||||
|65|Garage|Ved yderdør|Tryk 6 tast|12|Tryk NH|||||
|||||||||||

#### Røgsensor

||Lokalitet|Placering____*****|Komponent|Kabel|Terminal|Farve|I/O Interface|||||
|:---:|:---|:---|:---|:---:|:---|:---|:---|:---:|:---:|:---:|:---:|
|66|Stue||Røgsensor|||Indgang 4|18|Orange|Udgang 7|02||
|67|Soveværelse||Røgsensor|||Indgang 2|18|Hvid |Udgang 7|02||
|68|Bryggers|I loft|Røgsensor|36||Indgang 3|07|Sort|Udgang 7|02|Violet|
|69|Garage||Røgsensor|||Indgang 4|17||Udgang 7|02|
|70|Udendørs|Indkørsel|Røgsensor|||Indgang 5||Grøn|Udgang 7|03|HvidBlå|
|||||||||||||

#### Pir

||Lokalitet|Placering____*****|Komponent|Kabel|Terminal|Farve|I/O Interface|||||
|:---:|:---|:---|:---|:---:|:---|:---|:---|:---:|:---:|:---:|:---:|
|71|Stue|På væg|Pir|33|Alarm|Indgang 3|18|Sort|||
|72|Soveværelse|Ved dør til toilet|Pir||Tilstede|Indgang 5|08|Hvid|||
|73|Bryggers|På væg|Pir|31|Alarm|Indgang 3|16|Sort|||
|74|Garage|På væg|Pir|30|Alarm|Indgang 3|15|Sort|||

### Output

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

---------------------------------------------------------------------------------------------------------------------

## IHC (gammel installation)

### Input og Output

* [LK_IHC_Control_Installationsdokumentation.pdf](./LK_IHC_Control_Installationsdokumentation.pdf)
  * [InputOutput.ods](./InputOutput.ods)
  * [InputOutput.xls](./InputOutput.xls)

#### Input

||Lokalitet|Placering|Komponent|Kabel|Terminal|IHC Modul|Ledning|Farve|Forsyning|Ledning2||
|:---:|:---|:---|:---|:---:|:---|:---|:---:|:---:|:---:|:---:|:---:|
|0|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk ØV|Indgang 1|01|Sort||||
|1|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk ØH|Indgang 1|02|Grøn||||
|2|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk NV|Indgang 1|03|Violet|||
|3|Lille Bad|Ved dør|Tryk 4 tast|1|Tryk NH|Indgang 1|04|Brun|||
|||||||||||||
|4|Værelse(2)|Ved dør|Tryk 4 tast|2|Tryk ØV|Indgang ?|--|||
|5|Værelse(2)|Ved dør|Tryk 4 tast|2|Tryk ØH|Indgang 1|05|Grøn|||
|6|Værelse(2)|Ved dør|Tryk 4 tast|2|Tryk NV|Indgang ?|--|||
|7|Værelse(2)|Ved dør|Tryk 4 tast|2|Tryk NH|Indgang 1|06|Brun|||
|||||||||||||
|8|Værelse(8)|Ved dør|Tryk 4 tast|3|Tryk ØV|Indgang 1|07|Sort|||
|9|Værelse(8)|Ved dør|Tryk 4 tast|3|Tryk ØH|Indgang ?|--||||
|10|Værelse(8)|Ved dør|Tryk 4 tast|3|Tryk NV|Indgang 1|08|Violet|||
|11|Værelse(8)|Ved dør|Tryk 4 tast|3|Tryk NH|Indgang ?|--||||
|||||||||||||
|12|Garage|Ved dør|Tryk 6 tast|4|Tryk ØV|Indgang 1|15|Sort|||
|13|Garage|Ved dør|Tryk 6 tast|4|Tryk ØH|Indgang 1|16|Grøn|||
|14|Garage|Ved dør|Tryk 6 tast|4|Tryk MV|Indgang ?|--||||
|15|Garage|Ved dør|Tryk 6 tast|4|Tryk MH|Indgang ?|--||||
|16|Garage|Ved dør|Tryk 6 tast|4|Tryk NV|Indgang 1|17|Rød|||
|17|Garage|Ved dør|Tryk 6 tast|4|Tryk NH|Indgang ?|--||||
|||||||||||||
|18|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk ØV|Indgang 2|01|Sort|||
|19|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk ØH|Indgang 2|02|Grøn|||
|20|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk MV|Indgang 2|03|Violet|||
|21|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk MH|Indgang ?|--||||
|22|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk NV|Indgang 2|04|Rød|||
|23|Køkken|Ved dør til bryggers|Tryk 6 tast|5|Tryk NH|Indgang 2|05|Grå|||
|||||||||||||
|24|Stue|På væg|Tryk 6 tast|6|Tryk ØV|Indgang 2|12|Sort|||
|25|Stue|På væg|Tryk 6 tast|6|Tryk ØH  |Indgang 2|13|Grøn|||
|26|Stue|På væg|Tryk 6 tast|6|Tryk MV|Indgang 2|14|Violet|||
|27|Stue|På væg|Tryk 6 tast|6|Tryk MH|Indgang ?|--||||
|28|Stue|På væg|Tryk 6 tast|6|Tryk NV|Indgang 2|15|Rød|||
|29|Stue|På væg|Tryk 6 tast|6|Tryk NH|Indgang 2|16|Grå|||
|||||||||||||
|30|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk ØV|Indgang 3|08|Sort|||
|31|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk ØH|Indgang 3|11|Grøn|||
|32|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk MV|Indgang 3|12|Violet|||
|33|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk MH|Indgang 3|13|Brun|||
|34|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk NV|Indgang 3|14|Rød|||
|35|Entré|Ved dør til køkken|Tryk 6 tast|7|Tryk NH|Indgang ?|--||||
|||||||||||||
|36|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk ØV|Indgang 3|01|Sort|||
|37|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk ØH|Indgang 3|02|Grøn|||
|38|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk MV|Indgang 3|03|Violet|||
|39|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk MH|Indgang 3|04|Brun|||
|40|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk NV|Indgang 3|05|Rød|||
|41|Soveværelse|Ved dør til st. bad|Tryk 6 tast|8|Tryk NH|Indgang 3|06|Grå|||
|||||||||||||
|42|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk ØV|Indgang 4|01|Sort|||
|43|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk ØH|Indgang 4|02|Grøn|||
|44|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk NV|Indgang 4|03|Violet|||
|45|Soveværelse|Ved seng V|Tryk 4 tast|9|Tryk NH|Indgang 4|04|Brun|||
|||||||||||||
|46|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk ØV|Indgang 4|05|Rød|||
|47|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk ØH|Indgang 4|06|Hvid|||
|48|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk NV|Indgang 4|07|Orange|||
|49|Soveværelse|Ved seng H|Tryk 4 tast|9|Tryk NH|Indgang 4|08|Gul|||
|||||||||||||
|50|Entré|Ved yderdør|Tryk 4 tast|10|Tryk ØV|Indgang 4|11|Sort|||
|51|Entré|Ved yderdør|Tryk 4 tast|10|Tryk ØH|Indgang 4|12|Grøn|||
|52|Entré|Ved yderdør|Tryk 4 tast|10|Tryk NV|Indgang 4|13|Violet|||
|53|Entré|Ved yderdør|Tryk 4 tast|10|Tryk NH|Indgang ?|--|||
|||||||||||||
|54|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk ØV|Indgang 2|06|Sort|||
|55|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk ØH|Indgang 2|07|Grøn|||
|56|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk MV|Indgang ?|--||||
|57|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk MH|Indgang ?|--||||
|58|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk NV|Indgang 2|08|Rød|||
|59|Køkken|Ved dør til viktualrum|Tryk 6 tast|11|Tryk NH|Indgang 2|11|Grå|||
|||||||||||||
|60|Garage|Ved yderdør|Tryk 6 tast|12|Tryk ØV|Indgang 1|11|Sort|||
|61|Garage|Ved yderdør|Tryk 6 tast|12|Tryk ØH|Indgang 1|12|Grøn|||
|62|Garage|Ved yderdør|Tryk 6 tast|12|Tryk MV|Indgang 1|13|Violet|||
|63|Garage|Ved yderdør|Tryk 6 tast|12|Tryk MH|Indgang ?|--||||
|64|Garage|Ved yderdør|Tryk 6 tast|12|Tryk NV|Indgang 1|14|Rød|||
|65|Garage|Ved yderdør|Tryk 6 tast|12|Tryk NH|Indgang ?|--||||
|||||||||||||
|66|Stue||Røgsensor|||Indgang 4|18|Orange|Udgang 7|02||
|67|Soveværelse||Røgsensor|||Indgang 2|18|Hvid |Udgang 7|02||
|68|Bryggers|I loft|Røgsensor|36||Indgang 3|07|Sort|Udgang 7|02|Violet|
|69|Garage||Røgsensor|||Indgang 4|17||Udgang 7|02|
|70|Udendørs|Indkørsel|Røgsensor|||Indgang 5||Grøn|Udgang 7|03|HvidBlå|
|||||||||||
|71|Stue|På væg|Pir|33|Alarm|Indgang 3|18|Sort|||
|72|Soveværelse|Ved dør til toilet|Pir||Tilstede|Indgang 5|08|Hvid|||
|73|Bryggers|På væg|Pir|31|Alarm|Indgang 3|16|Sort|||
|74|Garage|På væg|Pir|30|Alarm|Indgang 3|15|Sort|||

#### Output

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
