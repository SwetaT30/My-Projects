# My-Projects

# Project 1 : IBM HR Attrition Analysis Dashboard

![Page 1 Dashboard](https://github.com/user-attachments/assets/d86b8971-fab3-450b-ba0b-dff570661bac)

![Page 2 Dashboard](https://github.com/user-attachments/assets/5ca96686-3848-450e-8ec4-2f2f0e1d62b9)

## Objective

Create an interactive and user-friendly Dashboard for analyzing the key HR KPIs like Employee Count, Average Age of Employees, Gender Ratio, Average Salary, Various Job Roles, etc., contributing to attrition of the employees in IBM Company. This project provides in-depth analysis of the factors responsible for employee's attrition patterns in the company and help identify the factors that influence employee turnover and retention. It aims to streamline Data Analysis Process for the company by helping them gain insights into areas with high attrition rates to inform targeted retention strategies.

## Dataset

**The dataset contains 1470 rows and 35 columns, including :**

Age  
Attrition  
Business Travel  
Daily Rate  
Department  
Distance From Home  
Education  
Education Field  
Employee Count  
Employee Number  
Environment Satisfaction  
Gender  
Hourly Rate  
Job Involvement  
Job Level  
Job Role  
Job Satisfaction  
Marital Status  
Monthly Income  
Monthly Rate  
Num Companies Worked  
Over 18  
Over Time  
Percent Salary Hike  
Performance Rating  
Relationship Satisfaction  
Standard Hours  
Stock Option Level  
Total Working Years  
Training Times Last Year  
Work Life Balance  
Years At Company  
Years In Current Role  
Years Since Last Promotion  
Years With Curr Manager  

## Technology Stack

**Data Sources :** CSV, Excel, PDF  
**Tools :** Excel, PowerBI, Power Query, DAX  

## Steps and Workflow

1. **Data Extraction**

Imported the **IBM HR Analytics Employee Attrition & Performance** Dataset from Kaggle in **CSV** format. This HR Dataset contains information about 1470 employees, such as their age, gender, department, job role, salary, education, performance, satisfaction, attrition, etc.  
Then, coverted it into an **Excel** format in order to perform the process of Data Cleaning and Preprocessing.  
Next, updated the headers of all the columns. Then, applied filters on all the columns and checked for any outliers or anomalies in the data set and decided whether to keep them or remove them. Removed the duplicate or null values from the dataset. Also, Modified the text entries in some columns using Find and Replace Methods to make them easy to understand.
Added two additional columns **Age Groups** and **Salary Slab** next to Columns **Age** and **Monthly Income** respectively for performing data analysis and visualization steps in power BI.

2. **Data Integration**

Imported the dataset from my system into **Power BI** in Excel format.

3. **Data Transformation**

After importing the dataset, used the Power Query Editor to perform any further data cleaning, transformation or validation that was needed for report building such as checked the datatypes of each of the columns and updated them as per the column values.  
Also created few more additional columns such as **Attrition Count** for dashboard creation. Finally, clicked on **Close and Apply** button in Power Query Editor and my dataset was ready for Dashboard Preparation.

4. **Defining the KPIs and Advanced DAX Calculations**

**KPIs** and **DAX Measures** are the core elements that drive the dashboard and display the data in a meaningful and actionable way. KPIs and DAX measures should be relevant, accurate and simple and should match the business requirement and the audience’s needs and expectations.   
Created dynamic DAX Measures for KPIs such as **Attrition Rate**, **Average Age**, **Employee Count**, **Monthly Salary**, etc.

5 . **Dashboard Design**

A dashboard layout and visualizations are the visual elements that make up the dashboard and display the data attractively and understandably.  
**Created KPIs using Cards** : Count of Employees, Attrition, Attrition Rate, Average Age, Average Salary, Average Years  
**Created Slicers** : Department, Education Field, Age Groups, Salary Slab, Gender  
**Created Visuals** :  
Page 1  
Attrition by Education - Donut Chart  
Attrition by Age - Column Chart  
Attrition by Salary - Bar Chart  
Attrition by Years - Area Chart  
Attrition by Job Role - Bar Chart  
Table Showing Total Attrition Count by Job Role and Job Satisfaction  
Attrition by Gender - Treemap  

Page 2  
Attrition by Total working Years - Area Chart  
Attrition by Business Travel - Column Chart  
Attrition by Department - Pie Chart  
Attrition by Marital Status - Donut Chart  
Attrition by Job Level - Bar Chart  
Attrition by Performance Rating - Treemap  

## Key Insights

>> The total employee attrition count is 237 with an overall attrition rate of 16%. The main reasons for attrition are low salaries, job dissatisfaction and lack of career growth opportunities.  
>> The majority of employees leaving the company are in the age group of 26-35 (97) and 36-45 (38). The average age of employees facing attrition is 37.  
>> The employee diversity and inclusion analysis reveals that there is a significant gap in gender representation, where only 34% are females.  
>> The attrition rate in education field is dominated by Life Sciences & Medical, which accounts for more than 60% of the employees.  
>> Employees with the lowest salaries (upto 5k),; those who are earning lower than the average salary (6.5k) have higher attrition rates (54%).  
>> Employees having less work experience in years (1-2) tend to leave the company at a higher rate than those having more years of experience.  
>> Among Job Roles, Laboratory Technician are the ones with highest attrition counts (62), followed by Sales Executive (57) and Research Scientist (47).  
>> Employees who travel rarely for business have a higher attrition rate (65%) compared to those who travel frequently (29%).  
>> Attrition rates vary across departments, with R&D (56%) having the highest rates, followed by Sales (39%) and HR (5%).  
>> Single employees face a higher rate of attrition compared to married or divorced employees.  
>> Attrition rates vary significantly based on job satisfaction levels; employees with lower job satisfaction levels have higher attrition rates.  
