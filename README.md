# HR_DATA _ANALYSIS_DASHBOARD
## Goal of the project
To build an HR data analysis dashboard that provides insights into increasing employee retention time and rates, reducing attrition, and optimizing recruitment and performance metrics to enhance workforce stability and engagement

 - The **OBJECTIVE** of this project is to help an organization to improve employee retection time (Reduce Attrition) by creating an **HR Analysis Dashboard**


## Power BI Dashboard
The HR Analysis Dashboard can be found [here](https://github.com/user-attachments/files/17407384/HR_Data_Analysis.pdf)



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




