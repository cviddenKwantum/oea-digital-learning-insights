# Data Dependencies

This package combines multiple data sources which were identified through the concepts of using student information data 

* **School Information System (SIS)**: Student school, grade, roster, and demographics data
* **Barriers to students**: Financial status, connectivity behavior, and digital access
* **Device Assignment**: Device information, student assignment
* **Access/Connectivity data**: Upload/Download speed, latency, request processing time, etc.
* **Attendance data**: Digital attendance

## Digital Access/Connectivity Data

To quantify student digital access inside and outside of school, digital signals considered are variable. Values were filtered by ISP (Internet service provider), to account for whether the access signal collected was from inside or outside of school.

As this package stands, currently there is not a module to support the connectivity data used in production of this package.

## Power BI Data Model

Below is a view of the data model used in Power BI visualizations. The primary tables and relationships can be seen.
* **model_pbi Table**: Data used to train predictive model and model results.
* **studentattendanceaggregate Table**: Time dependent records of student attendance.
* **model_log Table**: Log of all model assessment results used for model development.
* **attendancegroups Table**: Grouping of attendance codes.
* **school_location Table**: School locations for visualizations.
* Various order and recoding tables.

![](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/PowerBiDataModel.png)
