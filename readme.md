# OEA Digital Learning Insights Packages

<strong><em>\[EDIT\]</strong></em>

This collection of OEA Digital Learning Packages contains technical resources for a variety of common education use cases, related to predicting whether a student needs specialized support. Depending on their context, students may need academic support for specific skills or knowledge domains; they may need support to ensure they can attend and engage in school; or they may need support with their home, health, or safety context. The OEA community has identified three primary categories of student supports that are needed in both primary, secondary and post-secondary education systems.

![alt text](https://github.com/cstohlmann/oea-digital-equity/blob/main/images/Digital%20Learning%20Insights%20Packages.png)

<strong><em>\[EDIT\]</strong></em>

The OEA packages in this collection can be used to set up the data resources, stakeholder engagement, responsible AI processes, machine learning models, and dashboards that can identify patterns of supports needed and predict which individual students are likely to become in need of supports. The predictions can help education systems and schools choose the right methods of intervention to reduce or prevent student challenges and better support each student’s success.

Each use case package includes Use Case Documentation that provides guidance on the end-to-end process of developing a successful use case project, including how to engage stakeholders in the project, prior research on the use case problem domain and theory, how to map data sources to the theory of the problem, and how to implement principles of responsible data and AI in the process of predictive modelling.

## Library of Digital Learning Insights Use-Cases

The table below describes the use-cases that can be addressed through the OEA Digital Learning Insights packages.

| [Digital Equity of Access](https://github.com/cstohlmann/oea-digital-equity/tree/main/Digital_Equity_of_Access) | [Digital Engagement](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Engagement) | [Student Well-Being](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Wellness) | [Student Digital Learning](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Digital_Learning) |
| --- | --- | --- | --- |
| Equity - identifying students who do not have quality digital learning access outside school | Present patterns of digital engagement across digital learning ecosystem (all apps and learning resources), relative to access | Patterns of student well-being, (i.e. social-emotional competencies) | Show relationship between app-use and learning outcomes (assessment, knowledge checks, grades, completion/graduation, skills) |
| Identify locations that need better connectivity | Predict patterns of digital engagement to notify educators and schools of potential dis-engagement | Show relationship between access, engagement, learning and well-being | Identify and predict where student academic declines (at-risk) may happen | 
| Predict costs of ensuring equity of maintaining access to digital learning (devices + connectivity) | Identify work \& engagement patterns of staff who are working remotely | Well-being interventions tracking \& <em>de-stigmatizing mental health (may be at risk)</em> | Personalization - metadata on curriculum resources |
| | Hybrid engagement (physical attendance + digital engagement) |  | Recommendations to teachers on curriculum areas / apps |
|  | Student and staff digital activity during and outside of school hours by location (in school or out of school) |  |  |


## Data Requirements (and OEA modules)

The table below outlines the types of data sources that are most often used to report and develop the models for each category of these Digital Learning Insights packages.

<strong><em>Note: The assets provided within each of these use-case templates are general solutions. This means that they can use specific OEA modules, but they can also use other data sources that an education system or school has.</strong></em>

| [Digital Equity of Access](https://github.com/cstohlmann/oea-digital-equity/tree/main/Digital_Equity_of_Access) | [Digital Engagement](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Digital_Engagement) | [Student Well-Being](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Wellness) | [Student Digital Learning](https://github.com/cstohlmann/oea-digital-learning-insights/tree/main/Student_Digital_Learning) |
| --- | --- | --- | --- |
| SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed | SIS or MIS Data: Attendance, school, department, course rosters, class subject, grade level, student behavior, and demographics as needed |
| Device Signal <MDM audit log> (AAD / Intune / SCCM / Mobile Device Management + Inventory System) | Platform \& App signals (Clever, MS Graph, Edu Insights, iReady) - Caliper standard | Reflect data (Insights) | Assessment data - from standardized tests |  
| Internet performance \& location (GPS coordinates or Public IP address) MS Graph source? Global: check with <strong>MS Airband</strong> | LMS Data | Social-emotional learning \& competencies data | In-app assessments (Ed-Fi Assessment, iReady Assessment, Insights Grades) - LMS gradebooks | 
| Platform \& App signals (Clever, MS Graph, Edu Insights, iReady) - Caliper standard | | Sentiment Analysis | Completion/Graduation data |
| Time of day relative to school hours - timestamp | | | |
| Location of use (in school/out of school) - schools (Ed-Fi) | | | |
