# Project Pipelines

The OEA Chronic Absenteeism Package implements all data processing, machine learning model training, and production data processing by using [Synapse Pipelines](https://docs.microsoft.com/en-us/azure/data-factory/concepts-pipelines-activities?toc=%2Fazure%2Fsynapse-analytics%2Ftoc.json&tabs=data-factory). 

## Main Pipeline

The [main pipeline](https://github.com/cviddenKwantum/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/p_main.png) consists of 3 main sub-pipelines outlined in the below image. 

![Main Synapse Pipeline](https://github.com/cviddenKwantum/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/p_main.png "Main Pipeline")

### Step 1: Data Cleaning and Aggregation
 
The [first sub-pipeline](https://github.com/microsoft/OpenEduAnalytics/blob/main/packages/Chronic_Absenteeism/pipelines/p1_data_clean_aggr_support_VSTS.zip) does basic data cleaning and aggregation. Each data scource has a separate notebook. Processed data is written to Stage 3 to be access later downstream.

![Data Cleaning Pipeline](https://github.com/cviddenKwantum/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/p1_dataagg.png "Data Cleaning Pipeline")

### Step 2: Build PowerBI Data Model

The [second sub-pipeline](https://github.com/microsoft/OpenEduAnalytics/blob/main/packages/Chronic_Absenteeism/pipelines/p1_data_clean_aggr_support_VSTS.zip) does basic data cleaning and aggregation. Each data scource has a separate notebook. Processed data is written to Stage 3 to be access later downstream.

![PowerBI Data Model](https://github.com/cviddenKwantum/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/p2_pbimodel.png "PowerBI Data Model")

### Step 3: Create SQL View to Serve to PowerBI
 
The [final sub-pipeline](https://github.com/microsoft/OpenEduAnalytics/blob/main/packages/Chronic_Absenteeism/pipelines/p4_pbi_serve_support_VSTS.zip) prepares the final tables needed to support PowerBI dashboards.
![Power BI Pipeline](https://github.com/microsoft/OpenEduAnalytics/blob/main/packages/Chronic_Absenteeism/docs/images/p4.png "PowerBI Pipeline")
