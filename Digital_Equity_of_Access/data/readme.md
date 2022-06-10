# Data Dependencies

This package combines multiple data sources which were identified through the concepts of using student information data 

* **School Information System (SIS)**: Student school, grade, roster, and demographics data
* **Access/Connectivity data**: Upload/Download speed, latency, request processing time, etc. of log-ins
* **Barriers to students**: Financial status, connectivity behavior, and digital access
* **Device Assignment**: Device information, student assignment

## Digital Access/Connectivity Data

To quantify student digital access inside and outside of school, the digital signals considered are subject to change depending on data provided from access/connectivity data. Values were filtered by ISP (Internet service provider), to account for whether the access signal collected was from inside or outside of school.

As this package stands, currently there is not a module to support the connectivity data used in production of this package.

In the development with this package, MyQoI was used as this source of connectivity. Due to privacy concerns contained within the data from MyQoI, access signals from students were associated with the schools that any particular student was attending, thus not infringing on the privacy of those students. MyQoI provides a few different metrics that could have used for defining "low quality access connectivity" (e.g. latency of the access signal), and, within the development of this package, was explicitly defined as student-access signals with: 
* <em>Download Speeds</em> less than or equal to 25 Mbps, and
* <em>Upload Speeds</em> less than or equal to 3 Mbps.

This definition can vary across education institutions, and can be incorporated in the dashboard.

## Device Assignment Data

In the development of this package, Destiny was used as the primary data source for student-assigned device management. These devices were district-issued and contained information on: the device serial number, the type of device (e.g. laptop or tablet), the student ID the device was issued to, the status of the device, when the device was checked out, etc.

The [Intune Reports Module](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/Microsoft_Data/Intune) can be used as an alternative to understand the patterns of accessibility of students, based on whether they've been assigned devices. Other exploratory methods of analysis can be used to see if students benefit from issuing devices, and backing suggestions for other means of intervention or student-support.

## Power BI Data Model

Below is a view of the data model used in Power BI visualizations. The primary tables and relationships can be seen.
* **Destiny_Identity Table**: Data used to relay student device assignment by the education system.
* **myQoI_SIS_Identity_Groups Table**: Time dependent records of student connectivity data joined with SIS demographics data.
* **Identity_Maps Table**: Connects student IDs with other, synonymous, student IDs.
* **SIS_StudentSchool Table**: Connects student IDs to the schools they attend.
* **SIS_StaffStudentMap Table**: Data used to connect students with their current class(es)/teacher(s).
* Various other tables including: school locations, etc.

![](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/Digital_Equity_of_Access/docs/images/PowerBiDataModel.png)
