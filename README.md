# reproschema-builder

Create mindlogger applet from a CSV table:

1. Convert any survey into the format of the data dictionary template below:


### template for CSV 

Variable / Field Name |	Section Header | Form Name  |	Field Type  |	multipleChoice	| Field Label |	Choices, Calculations, OR Slider Labels | minVal |  maxVal |	Branching Logic (Show field only if...) |
|------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| ------------| 
|          |            |        |            |               |              |              |          |           |        |     

+ **Variable / Field Name**
The id for the survey item (required) <br/>
+ **Section Header** 
Preamble for the survey item (leave blank if you don't want a preamble) <br/>
+ **Section Header** 
+ **Form Name**
Name of the activity the survey item is a part of <br/>
+ **Section Header** 
+ **Field Type**
Type of reponse for survey item, currenty supports: 
  + radio
  + select
  + slider
  + text
  + static
  + timeRange
  <br/>
  
+ **Section Header** 
+ **multipleChoice**
+ **Field Label**
+ **Choices, Calculations, OR Slider Labels**
+ **maxVal**
+ **minVal**
+ **Branching Logic (Show field only if...)**


### Usage: 
`node tools/RedCap2ReproSchema.js path_to_your_csv_file`
