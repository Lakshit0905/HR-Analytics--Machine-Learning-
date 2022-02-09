## HR Analytics-Machine Learning

This repo contains the HR Analytics project as part of my data science portfolio. The objective is to predict employee attrition using a HR dataset from IBM Watson Analytics Sample Data - [HR Employee Attrition & Performance](https://www.ibm.com/communities/analytics/watson-analytics-blog/hr-employee-attrition/) which contains employee data for 1,470 employees with various information about the employees.

## Problem Statement

Although some staff turnover is inevitable in any company, a high attrition rate is costly. Employee attrition is the overall turnover within a company as existing employees leave and new ones are hired. The attrition rate is usually calculated as the percentage of employees leaving the company over a specified period of time. Recruitment, hiring and training all involve financial costs and a new employee may not be immediately productive in terms of creating profit. The amount of time spent to interview and find a replacement, and the loss of productivity for several months while the new employee gets accustomed to the new role, are indirect costs to the company. These costs can significantly increase if executive-level or highest-paid employees are to be replaced. As such, the costs of replacing employees for most companies are often very significant.

An unusually high employee attrition rate is also considered indicative of problems within the company. Uncompetitive pay scales, micromanagement, ineffective human resource management (HRM) practices and unreasonable expectations can all lead to unacceptable levels of staff turnover. Understanding why and when employees are most likely to leave can lead to actions to improve employee retention as well as possibly planning new hiring in advance.

In this project, I will attempt to answer the following questions:

What is the probability of an employee leaving the company?
What are the key drivers of an employee leaving the company?
What are the recommendations or strategies that can be adopted to improve employee retention?
This is a standard supervised classification problem where the target or label is a binary variable, 0 (active employee), 1 (ex-employee). The objective is to predict employee attrition based on various information about the employee. I will also attempt to generate the probability of an employee leaving the company as our target variable.

## Data Set

The dataset used in this project is IBM Watson Analytics Sample Data - HR Employee Attrition & Performance. The dataset contains 1,470 rows corresponding to 1,470 employees with their various information. It is also available directly within Watson Analytics as Employee Performance. As mentioned on IBM website, the purpose of the dataset is to

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists.

If you have any feedback for this project, feel free to contact me via my L
