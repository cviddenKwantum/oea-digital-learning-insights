# Project Pipelines

The OEA Digital Equity of Access Package implements all data processing, and production data processing by using [Synapse Pipelines](https://docs.microsoft.com/en-us/azure/data-factory/concepts-pipelines-activities?toc=%2Fazure%2Fsynapse-analytics%2Ftoc.json&tabs=data-factory). 

## Main Pipeline

The [main pipeline]() consists of 3 main sub-pipelines outlined in the below image. 

![Main Synapse Pipeline](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/mainPipeline.png "Main Pipeline")

### Step 1: Data Cleaning and Aggregation
 
The [first sub-pipeline]() does basic data cleaning and aggregation. Each data scource has a separate notebook. Processed data is written to Stage 3 to be access later downstream.

![Data Cleaning Pipeline](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/p1.png "Data Cleaning Pipeline")
