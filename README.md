# reproschema-builder

Create mindlogger applet from a CSV table:

1. Convert any survey into the format of the data dictionary template below:


### template for CSV 

Variable / Field Name |	Section Header | Form Name  |	Field Type  |	multipleChoice	| Field Label |	Choices, Calculations, OR Slider Labels | minVal |  maxVal |	Branching Logic (Show field only if...) |
|------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| 
|          |            |        |            |               |              |              |          |           |        |     

+ **Variable / Field Name**
+ **Section Header** 
+ **Form Name**
+ **Field Type**
+ **multipleChoice**
+ **Field Label**
+ **Choices, Calculations, OR Slider Labels**
+ **maxVal**
+ **minVal**
+ **Branching Logic (Show field only if...)**


### Usage: 
`node tools/RedCap2ReproSchema.js path_to_your_csv_file`
