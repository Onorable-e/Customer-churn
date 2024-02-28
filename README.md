![Customer-Churn-Image](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/5e174b4e-b5e3-4c54-a3e1-bcaa3ccba787)

This is a Capstone Project Report for my Data Analytics course at [Datafied Academy](https://github.com/Datafyde) - Data Heroes Cohort. <br>
As a pivotal component of the course, this capstone project leverages data analytics techniques to explore factors influencing customer churn in the banking sector.

# Problem Statement 
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty. 
A bank is experiencing customer churn that is impacting overall customer satisfaction and revenue, as well as they lack insights into the factors influencing customer decisions to leave or stay with the bank. There is a need to identify and address factors contributing to customer churn proactively.

# Dataset Overview
The dataset contains information on 10,000 bank customers over six months. Each entry contains essential information like CustomerID, CreditScore, Geography, Gender, Tenure, Balance, and more.

Data Source: [Hotel Dataset](https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/data)

# Project Objective 
The objective of the project is to give a clear understanding of customer demographics, behaviors, and churn patterns, identify key features influencing customer churn, and provide strategic recommendations for the bank based on data-driven insights.

# Key Performance Indicators (KPIs)
We also defined metrics and KPIs that will help answer the business questions. Examples include: <br>
- Total customers <br>
- Churn rate <br>
- % retained

# Data Inspection

# Data Cleaning 
Some steps taken during the data cleaning are as follows:
- The values 1 and 0 in the HasCrCard column were replaced with "Has CrCard" and "No CrCard" respectively. <br>
- The values 1 and 0 in the IsActiveMember column were replaced with "Active" and "Not Active" respectively. <br>
- The values 1 and 0 in the Churned column were replaced with "Churned" and "Retained" respectively. <br>
- A column titled Credit_Score_Group was created to group the credit score into; Poor (300-579); Fair (580-669); Good (670-739); Very Good (740-799) and Excellent (800-850) <br>.
- An Age_Group column was also created to group the ages into; Young Adult (20-39); Middle Adult (40-59) and Old Age (60+). <br>
- A Credit_Score_Sort and Age_Group_Sort columns were created on power query to use in sorting Credit_Score_Group and Age_Group when visualising. 

## Dataset after cleaning
![Dataset after cleaning](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/6cc9de39-a65f-4b22-81df-3575bc4b6f3d)

# Visuals and Charts
The insights were represented using appropriate chart formats (e.g., donut charts and bar charts). For more in-depth information, interactive elements including slicer options were employed.

![Visual](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/48169d6f-964b-4a60-9e23-61570ca52256)

# Insights
Some of the important insights and trends highlighted from the visuals created include:
- The churned rate is about 20.4%.
- Germany (39.92%) has the highest churned rate based on location. 
