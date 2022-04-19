# Data Dependencies

This section of the package provides details regarding the schema changes made during data curation for the Power BI dashboard, 
and how other data sources or modules can be modified and used in place of other modules used out-of-the-box.

 - <strong>(Current) schema changes to be noted:</strong> 
 - <strong>Module/Data source initially used:</strong>
 - <strong>Data products created:</strong> 

<strong><em>[CONSIDER ADDING PICTURE OF SCHEMA/COLUMN MAPPINGS]</strong></em>

## Module/Data Source Dependencies
The data sources most frequently needed and used for developing insights into Digital Equity of Access include:
 - SIS or MS Data: Attendance, school, department, course rosters, class's subject, grade level, student behavior, and demographics as needed
 - Device Signal (AAD / Intune / SCCM / Mobile Device Management + Inventory System)
 - Internet performance & location (GPS coordinates or Public IP address) MS Graph source? Global: check with MS Airband
 - Platform & App signals (Clever, MS Graph, Edu Insights, iReady) - Caliper standard
 - Time of day relative to school hours - timestamp
 - Location of use (in school/out of school) - schools (Ed-Fi)

<strong><em>\[EDIT\]</strong></em>

For the Digital Equity of Access Use-Case developed with _____, several OEA modules were used:
1. Student Information System (SIS) Data module using Ed-Fi Data Standard Module,
2. Microsoft Education Insights Module for LMS Data,
3. iReady for student outcome data, and
4. Clever for other digital learning app use data.
