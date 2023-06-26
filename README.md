# HRDataAnalyticsDashboard

 Created HR report/dashboard with the flat file (excel file)

 KPI
Added the important measures like 
Attrition Count {If [Attrition] = 'Yes' THEN 1 ELSE 0}, Active Employee Count (Employee Count - Attrition Count), Attrition Rate (Attrition count/Active Employee Count)

Attrition by Gender
Lollipop chart showing the Attrition Count by Gender

Attrition by Department
Pie Chart showing the Attrition Count by Department

Number of Employee By Age
Created a bin/parameter which shows the age gap ( 2,3,4 years )  and created a filter for it
Bar chart showing employees by age group

Job Satisfaction Rating
Created a heat map for Job satisfaction of the employees 

Attrition by Education Feild
Created a bar chart by Attrition rate and education feild 	 

Attrition rate by gender based on age groups
Created a donut chart based on CF age band, gender and SUM(Attrition Count)
Created a MIN(1) function and duplicated it and merged the axis


