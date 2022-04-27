# OEA Digital Learning Insights Packages

This collection of OEA Digital Learning Packages contains technical resources for a variety of common education use cases, centered around supporting student learning based on inequities seen in access, engagement, well-being and learning outcomes. Depending on context, students may require additional support from ensuring equity of digital access (e.g. checking out digital equipment), to support centered around attendance and digital engagement inside and outside of school. The OEA community has identified four primary categories of significant digital learning insights that are needed in both primary, secondary and post-secondary education systems.

![alt text](https://github.com/cstohlmann/oea-digital-learning-insights/blob/main/images/Digital%20Learning%20Insights%20Packages.png)

The OEA packages in this collection can be used to set up the data resources, stakeholder engagement, and dashboards that can identify trends in student learning activities, expectations, and intervention-method successes. These dashboards can help education systems and schools understand categorical breakdowns of student learning (i.e. categories can include school, student demographics, grades, signals inside or outside of school, etc).

Each use case package includes Use Case Documentation that provides guidance on the end-to-end process of developing a successful use case project, including how to engage stakeholders in the project, prior research on the use case problem domain and theory, how to map data sources to the theory of the problem, and how to implement principles of responsible data modelling.

## Library of Digital Learning Insights Use-Cases

The table below describes the use-cases that can be addressed through the OEA Digital Learning Insights packages.

| [Digital Equity of Access](https://github.com/cstohlmann/oea-digital-equity/tree/main/Digital_Equity_of_Access) | [Digital Engagement](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Engagement) | [Student Digital Learning](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Digital_Learning) |
| --- | --- | --- |
| Equity - identifying students who do not have quality digital learning access outside school | Present patterns of digital engagement across digital learning ecosystem (all apps and learning resources), relative to access  | Show relationship between app-use and learning outcomes (assessment, knowledge checks, grades, completion/graduation, skills) |
| Identify locations that need better connectivity | Predict patterns of digital engagement to notify educators and schools of potential dis-engagement | Identify and predict where student academic declines (at-risk) may happen | 
| Predict costs of ensuring equity of maintaining access to digital learning (devices + connectivity) | Identify work \& engagement patterns of staff who are working remotely | Personalization - metadata on curriculum resources |
| | Hybrid engagement (physical attendance + digital engagement) | Recommendations to teachers on curriculum areas / apps |
|  | Student and staff digital activity during and outside of school hours by location (in school or out of school) | |


## Data Requirements (and OEA modules)

The table below outlines the types of data sources that are most often used to report and develop the models for each category of these Digital Learning Insights packages.

<strong><em>Note: The assets provided within each of these use-case templates are general solutions. This means that they can use specific OEA modules, but they can also use other data sources that an education system or school has.</strong></em>

| [Digital Equity of Access](https://github.com/cstohlmann/oea-digital-equity/tree/main/Digital_Equity_of_Access) | [Digital Engagement](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Engagement) | [Student Well-Being](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Wellness) | [Student Digital Learning](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Digital_Learning) |
| --- | --- | --- | --- |
| SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed |
| Platform \& App signals (MS Graph) - Caliper standard | Platform \& App signals (Clever, MS Graph, Edu Insights, iReady) - Caliper standard | Reflect data (Insights) | Assessment data - from standardized tests |  
| Connectivity Data (i.e. GPS coordinates or Public IP address. Location and Time Data should be included): MS Graph, check <strong>MS Airband</strong>, MyQoI | LMS Data | Social-emotional learning \& competencies data | In-app assessments (Ed-Fi Assessment, iReady Assessment, Insights Grades) - LMS gradebooks | 
| Device Assignment Data: <MDM audit log> AAD, Intune, SCCM, Mobile Device Management + Inventory System, Destiny | | Sentiment Analysis | Completion/Graduation data | 
