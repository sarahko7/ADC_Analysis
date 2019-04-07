# ADC Dataset

## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019

The dataset contains data on CalRecycle-approved alternative daily cover used in California, USA. The California Department of Resources Recycling and Recovery (also known as 'CalRecycle') is a department within the California Environmental Protection Agency. 

## Database Information
Data were collected from the CalRecycle website. More information can be found here: https://www.calrecycle.ca.gov/AboutUs/

Data were collected using the Data tool (https://www2.calrecycle.ca.gov/LGCentral/DisposalReporting/Statewide/ADCByMaterialType).
From the URL page, the following selection was made: 
* Export to Excel

The file was then converted to a CSV file with the following actions: 
* file > save as > select file type 'CSV (Comma delimited)(*.csv)'

Data were accessed 2019-04-06 (April 6, 2019).

## Data Content Information
The quantities of ADC are reported in units of U.S. tons, which is equivalent to 2000 lbs. 

From the CalRecycle site: 

### Statewide Alternative Daily Cover (ADC) by Material Type
ADC means CalRecycle-approved materials other than soil used as a temporary overlay on an exposed landfill face. Complete ADC by material type available starting in 1998. Prior to 1998 all ADC is categorized as "Other".

## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Sarah Ko** (sarah.ko@duke.edu)