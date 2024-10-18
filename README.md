# HR_DATA _ANALYSIS_DASHBOARD
## Goal of the project
To build an HR data analysis dashboard that provides insights into increasing employee retention time and rates, reducing attrition, and optimizing recruitment and performance metrics to enhance workforce stability and engagement

 - The **OBJECTIVE** of this project is to help an organization to improve employee retection time (Reduce Attrition) by creating an **HR Analysis Dashboard**


## Power BI Dashboard
The HR Analysis Dashboard can be found [here](https://github.com/Taneshkumar90/HR_DATA-_ANALYSIS_DASHBOARD/blob/main/HR_Data_Analysis%20(1).pdf)



<p align="center">
  <img src="https://github.com/user-attachments/assets/ea6f1fb5-c745-40ec-874e-e1fcb5f6613b" alt="HR Dashboard" width="900">
</p>

## Analysis Approach
### 1. Data Quality Assessment and Data Cleaning
The first step towards generating useful insights from the data was the data prepartion, quality assessment and data cleaning step. After the cleaning process exploratory data analysis on the dataset and identification Attriton distribution and relations between/among attributes to generate insights can be performed.

In the data cleaning step the data quality of the following datasets were first assesed. After a data quality assessment the following data quality issues was observed and the necessary process to mitigate the issue was followed :
- <b>HR_danalysis</b> :
  - 2 Irrelevent column was present and such columns were dropped from the dataset.
  - There were 2 columns had Missing values, for such columns based on the volumne of the missing values either the records were dropped or appropiate values(Mode) were imputed at places of missing values
  - The Date of Joining column was transformed to create a new feature column 'Age' and 'Age Group' to check for discripency of age distribution . An <b>outlier</b> (above 35)was observed and the record was removed.
    -Checked Formats of all attributes of dataset 
  - Checked whether there are duplicate records present in the dataset. In this dataset there were no duplicate records.

   ### 2. Exploratory Data Analysis on Attrition in organization
After the data cleaning process, exploratory analysis on the dataset is performed and the following insights are obtained :

- <b>Key Descriptive Statistics</b> :
  - Number of **total employees** in the organization   = 1416
  - number of total employees who left the organization = 229
  - **Attrition** in the organization                       = 16.17%
  -  **Average Years at organizaton** empoyees worked       = 7 yr
  -  **Average Age** of employees                               = 36.92 yr
  -  **Average Salary** of employees                        = 6.5k $


- <b>Attrition by **education field** of employees </b> :
   - Life Science Education Field  holds **Most Attrition percentage** 38.4% of all Attrition in Organization based on Eduation Field
  - Human Resources holds The lowest Percentage less than 3% of all Attrition in Organization 
  - **Technical Degree** and **marketing** Education Fields almost have same attribution percentage around 24% 
 <p align="left">
  <img src="https://github.com/user-attachments/assets/83bc8e3e-c8fe-45a9-9171-f0e9e2d7c11e" alt="Attrition by Education Field" width="400">
</p>

- <b>Attrition by **Age Gruop** of employees </b> :
  
   - **Most number of attrition** in 26-35 Age gruop  111 
   - 35+ Age gruop have The **lowest Attrition number**  less than 10 
   - A steep drop observed attrition after 26-30 age gruop
 
 <p align="left">
  <img src="https://github.com/user-attachments/assets/3913f139-d198-4478-b156-78ef81cc317a" alt="Attrition by Education Field" width="400">
</p> 

- <b>**Job satisfaction rating**  based on job role </b> :
  
  - Healthcare Representative and Sales Representative have have more 4 star rating based on total number of rating given to each job Role
  - Laboratory Technician Manager Job role give lowest job satisfaction rating (18 bad rating)
  - Mostly highest given to each job role is 3 star
 
 <p align="left">
  <img src="https://github.com/user-attachments/assets/83ede614-df62-46c8-92d0-2f8416d94a52" alt="Attrition by Education Field" width="400">
</p> 

- <b>Attrition by **Salary Gruop** of employees </b> :
  
   - **Most number of attrition** in up to 5k $ salary gruop  158 which very crucial metrics 
   - 15k+ Salary gruop have The **lowest Attrition number**  less than 5 
   - A steep drop observed attrition after 5k salary slary gruop
 
 <p align="left">
  <img src="https://github.com/user-attachments/assets/201ae639-874e-42cc-a3a0-735fb40fb812" alt="Attrition by Education Field" width="400">
</p> 

- <b>Attrition by **Years At Company** of employees </b> :
  
   - Mostly employees left the company  within or after just 1 year
  - After 3 years mostly employees retained in company 
  - After 11 years none of employees left the companly
 <p align="left">
  <img src="https://github.com/user-attachments/assets/209d9e41-d43a-44a0-a6b6-1c1fd62b175a" alt="Attrition by Education Field" width="400">
</p>


- <b>Attrition by **Job Role** in company </b> :
  
   - Mostly Sales Executive employees(55) left the company
  - Least Attrition (2) in Research Director
 <p align="left">
  <img src="https://github.com/user-attachments/assets/250a6a47-3459-4f4c-9739-7f93486d0c92" alt="Attrition by Education Field" width="400">
</p>
  
## Datasets Used
The datasets used include:
- HR_Analytics.csv: This excel file dataset included the following Attributes:

   - EmpID: Includes ID of employees
   - Age : Age of employees
   - AgeGroup	Attrition : Age group of employees created based on Age columns
   - Department : Department in which employees are working
   - EducationField : Education Field related to each employees
   - EmployeeCount : No of employees (by counting distinct employee ID)
  	- Gender : Gender of employees
   - JobRole : Job role assigned to employee
  	- JobSatisfaction : Job satisfaction rating given by left employees
   - MonthlyIncome : Monthly income of each employee
   - SalarySlab : salary salabs created by using on monthly income  
	  - YearsAtCompany : working years of Employees in company 


## Tools and Technologies used
The tools used in this project include:
- __POWER BI__ - This <b>Business Intelligence</b> tool was required to explore data and create charts, graphs, visualizations to come up with a <b>HR Data Analysis </b> for the  company. The Power BI HR ANALYSIS Dashboard can be found [here](https://github.com/Taneshkumar90/HR_DATA-_ANALYSIS_DASHBOARD/blob/main/HR_Data_Analysis%20(1).pdf)



