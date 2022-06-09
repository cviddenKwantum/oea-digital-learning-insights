# Data Dependencies

This package combines multiple data sources which were identified through the concepts of using student information data 

* **School Information System (SIS)**: Student school, grade, roster, and demographics data
* **Access/Connectivity data**: Upload/Download speed, latency, request processing time, etc.
* **Barriers to students**: Financial status, connectivity behavior, and digital access
* **Device Assignment**: Device information, student assignment

## Digital Access/Connectivity Data

To quantify student digital access inside and outside of school, digital signals considered are variable. Values were filtered by ISP (Internet service provider), to account for whether the access signal collected was from inside or outside of school.

As this package stands, currently there is not a module to support the connectivity data used in production of this package.

## Power BI Data Model

Below is a view of the data model used in Power BI visualizations. The primary tables and relationships can be seen.
* **Destiny_Identity Table**: Data used to relay student device assignment by the education system.
* **myQoI_SIS_Identity_Groups Table**: Time dependent records of student connectivity data joined with SIS demographics data.
* **Identity_Maps Table**: Connects student IDs with other, synonymous, student IDs.
* **SIS_StudentSchool Table**: Connects student IDs to the schools they attend.
* **SIS_StaffStudentMap Table**: Data used to connect students with their current class(es)/teacher(s).
* Various other tables including: school locations, etc.

![](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/PowerBiDataModel.png)
