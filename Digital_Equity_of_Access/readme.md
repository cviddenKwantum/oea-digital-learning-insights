# Digital Learning Insights Package: Equity of Digital Access
The OEA Digital Equity of Access Package provides a set of assets which support an education system in developing their own data solution to address inequities in digital access. There are two main components of this package:

1. <ins>Guidance and documentation:</ins> The [OEA Equity of Digital Access Package - Documentation](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/docs) provides guidance on the end-to-end process of developing a successful Equity of Access use-case project, including how to engage stakeholders in the project, prior research on the use case problem domain and theory, how to map data sources to the theory of the problem, and how to implement Microsoft’s Principles of Responsible Data and AI. <em> It is highly recommended this document be reviewed by any education system considering using this package, and that the documentation be revised to the specific data and decisions for that system’s context. </em>
2. <ins>Technical assets:</ins> Various assets are freely available in this package to help accelerate implementation of Equity of Digital Access use cases. Assets include descriptions of data sources, notebooks for data processing, a pipeline for the OEA-standard data curation (i.e. aggregation, schema transformation, etc), and sample PowerBI dashboards. See descriptions of technical assets below.

This OEA Package was developed through a partnership between Microsoft Education, [Kwantum Analytics](https://www.kwantumanalytics.com/), and [Fresno Unified School District](https://www.fresnounified.org/) in Fresno, California.

## Problem Statement

Equity of digital access is generally defined as the determination of whether a particular demographic of the student population is digitally disadvantaged. Inequity of student digital access is a fundamental challenge for education systems which has dramatically increased as result of the global pandemic. The motivation for this problem comes from a central idea of researching whether general digital accessibility is a primary factor of student learning outcomes (and indicators such as tests), specifically: How the lack of access to the necessary tools within a class can undermine the growth and learning of students. Students with less availability and access to digital forms of learning are frequently seen to struggle in school, greater chance of not attending school, and higher odds of failing classes. 

Data analyses and identifying trends of low access, heavily rely on connectivity data as well as SIS data (i.e. school roster, student demographics and attendance data). The subsequent dashboard used to model these analyses and trends can be used to focus on areas of intervention methods of granting students digital access, with the goal of increasing student engagement, wellness, and access to tools.

## Package Impact

This package was developed in collaboration with [Fresno Unified School District](https://www.fresnounified.org/) in Fresno, California. 

In general, this package can be used by system or institutional leaders, school, or department leaders, support staff, and educators to:
 - <em>Accurately identify</em> demographic breakdowns in student (in)equity to digital access.
 - <em>Outline trends</em> in student log-ins and proportionate "low quality access" log-in attempts. 
 - <em>Understand location factors</em> of "low quality access" attempts in a safe manner.
 - <em>Provide granular context</em> to student access behaviors.

See below for examples of developed PowerBI dashboards.

Student Digital Access (Overview)  | Student Digital Access (Demographics) | Student Digital Access (Location)
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/cstohlmann/oea-at-risk-package/blob/main/Chronic_Absenteeism/docs/images/Chronic%20Absenteeism%20Dashboard%20Overview.png)  |  ![](https://github.com/cstohlmann/oea-at-risk-package/blob/main/Chronic_Absenteeism/docs/images/Chronic%20Absenteeism%20Drivers%20Dashboard.png) | ![](https://github.com/cstohlmann/oea-at-risk-package/blob/main/Chronic_Absenteeism/docs/images/Chronic%20Absenteeism%20Social%20Worker%20Dashboard.png)

## Data Sources

This package combines multiple data sources which were identified through evaluating the characteristics of digital equity: 
* <strong>School Information System (SIS)</strong>: School, grade level, and demographics
* <strong>Access/Connectivity data</strong>: Upload/Download speed, latency, request processing time, etc.
* <strong>Barriers to students</strong>: Financial status, connectivity behavior, and lack of digital access
* <strong>Device Assignment data</strong>: Device information, student assignment


This package can use several [OEA Modules](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules) to help ingest data sources that are typically used to understand patterns of digital inequity (see below for list of relevant OEA modules).  

| OEA Module | Description |
| --- | --- |
| [Ed-Fi Data Standards](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Education_Data_Standards/Ed-Fi) | For typical Student Information System (SIS) data, including school rosters, grade level and demographic information. |
| [Connectivity Data](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Data) | Such as [Microsoft Graph](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Data/Microsoft_Graph) data. |

This Digital Equity of Access package was developed by [Kwantum Analytics](https://www.kwantumanalytics.com/) in partnership with [Fresno Unified School District](https://www.fresnounified.org/) in Fresno, California. The architecture and reference implementation for all modules is built on [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) - with [Azure Data Lake Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction) as the storage backbone, and [Azure Active Directory](https://azure.microsoft.com/en-us/services/active-directory/) providing the role-based access control.

Assets in the Digital Equity of Access package include:

1. [Data](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/data): For understanding the data relationships and standardized schema mappings used for certain groups of data.
2. [Documentation](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/docs): For understanding how to deploy this package within your own context and interpret the results.
3. [Notebooks](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/notebooks): For cleaning, processing, and curating data within the data lake.
4. [Pipelines](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/pipelines): For a glimpse at the overarching data manipulation process (i.e., aggregation, subsetting, schema transformation, etc.), and support for PowerBI dashboards.
5. [PowerBI](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Equity_of_Access/powerbi): Templates for exploring, visualizing, and deriving insights from the data.

# Legal Notices
Microsoft and any contributors grant you a license to the Microsoft documentation and other content in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode), see the [LICENSE](https://github.com/microsoft/OpenEduAnalytics/blob/main/LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the [LICENSE-CODE](https://github.com/microsoft/OpenEduAnalytics/blob/main/LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries. The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks. Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents, or trademarks, whether by implication, estoppel or otherwise.
