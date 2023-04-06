## HR Data Analysis

This Dataset was Sorted from [Kaggle](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set). Thanks to Dr.Rich huebner and his teamfor creating and also making the Hr dataset to be available practice.

## Introduction

This is a Microsoft excel project on Human Resources Analysis. This HR dataset was created by  Dr. Carla Patalano and Dr. Rich Huebner, to  teach students how to use and analyze the data. This project is to analyze and visualize insights to answer human resources question.

## Project Objective

- To which Department Performs Well
- The Employment Rate and Termination rate
- What department is likely to have shortage in staffs.

## Data Tools
Pivot Table

## Data Cleaning/Manipulation

The dataset was imported to power query on Excel. It consists of 36 columns and 311 rows.
![](Uncleaned%20data%20(1).png)
![](Uncleaned%20data%20(2).png)
![](Uncleaned%20data%20(3).png)

### Steps Taken

- Converted DOB data type from text to date, then to age, then created age rang column for visualization purpose. The initial DOB column is removed.
- Replaced the values in marital id, from 0 and 1, to No and Yes.
- Renamed the MaritalDesc column to marital status. The initial marital status is removed
- Renamed the sex column as Gender as it had the proper identification for gender. The initial Sex column in the data table is removed.
- Changed salary data type from text to Currency ($)
- Renamed the Citindesc column to only citizen, also race
- Changed the data type of Date of hire and termination to Date data-type
- Removed job diversity fair column, it had plenty null vales and also, it is indicated on the recruitment process column and also position id column. To avoid data inconsistencies, it is removed.
- The termination reason column in the datasets, has value of everyone who had reason to terminated or that was terminated. Therefore, the TermId column is removed.
- The following columns were removed ; Zip code, department id, manager id, employee id, EmpstatusId, Hispanic/latino. These columns have alternatives in the data table for the analysis.

At the end of data cleaning, there is 26 columns and 311 rows. Here is what the cleaned data looks like.

![](Cleaned%20data.png)
![](Cleaned%20data%20(2).png)
![](Cleaned%20data%20(3).png)

## Data Visualization

In accordance to the objective	

- Departments with the highest performance score

![](IT%20Dept.png)
![](PerfScore.png)

According to the employee performance score, the IT/IS Department ranked of 84% at Fully meet criteria, having 12% at Exceeds criteria. Thus making the department rank 1st,. This could be as a result of having more younger people in department

- The Employment Rate and Termination rate

![](Emp%20Rate.png)
![](Term%20Rate.png)

The year 2011, has the highest employement rate while the year 2015 has the ighest termination rate of employees.

- What department is likely to have shortage in staffs

![](Prod%20Dept.png)
![](Term%20Reasons.png)

The charts above show how the Production department. has the highest absence in the company. Also since the year 2011 up to the year 2018, the department has high rate of Employee termination with more than 30 reason for termination. 
It can be said that employees in the Production department are likely to leave their work position every year.

## Conclusion/Recommendation

It is advisable that the company should look out for the Production department, how the terminations can be stopped and how it won't affect the company's growth.

Seminars, hangout, breaks can be encouraged in the company. This gives employees comfort and security.

It is advisable the company look out for people in ther prime ages, as most of them are willing to put time and efforts to the company's progress whilst building their own career. 

Also other department should be highly looked into, invest more into them and bring them up to high functionality phase.

