**HR Analytics Dashboard - Power BI

Overview 

This HR Analytics Dashboard provides insights into employee attrition, demographics, and 
salary distribution. Built in Power BI, the dashboard helps HR teams analyze attrition trends 
based on various factors like age, education, job role, and salary. 

Features 
 Key Metrics: 
o Total Employee Count 
o Attrition Count 
o Attrition Rate (%) 
o Average Age 
o Average Salary 
o Average Years at Company 
 Filters: 
o Department Selection (Human Resources, R&D, Sales) 
 Attrition Breakdown: 
o By Education 
o By Age Group 
o By Gender 
o By Salary Slab 
o By Years at Company 
o By Job Role 
Data Modeling 
 The dataset includes information on employees, their demographics, and attrition 
status. 
 A Quarterly Data column needs to be added to track attrition by quarters. 
 Relationship between employee attributes and attrition trends is mapped using Power 
BI’s Data Model. 
Steps to Add Quarterly Data in Power BI 
1. Open Power Query Editor. 
2. Ensure that the dataset has a Date column. 
3. Create a new Quarter column using the following DAX formula: 
Quarter = "Q" & FORMAT([Date], "Q") 
4. Use this new column in a bar chart or matrix visual to track attrition per quarter. 
5. Integrate the Quarterly Data into the existing visuals or create a new visual for it. 
How to Use the Dashboard 
1. Select a department to filter the data. 
2. View attrition trends by different parameters. 
3. Analyze salary distribution and its impact on attrition. 
4. Use the age and years-at-company visuals to understand workforce stability. 
5. (Once added) Use the Quarterly Data section to monitor seasonal attrition trends. 
Future Enhancements 
 Add interactive drill-downs for deeper analysis. 
 Introduce forecasting models to predict attrition trends. 
 Include Employee Satisfaction Score as an influencing factor. 
This dashboard helps HR professionals make data-driven decisions to reduce attrition and 
improve employee retention.
