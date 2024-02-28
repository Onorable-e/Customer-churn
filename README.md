![Customer-Churn-Image](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/5e174b4e-b5e3-4c54-a3e1-bcaa3ccba787)

This is a Capstone Project Report for my Data Analytics course at [Datafied Academy](https://github.com/Datafyde) - Data Heroes Cohort. <br>
As a pivotal component of the course, this capstone project leverages data analytics techniques to explore factors influencing customer churn in the banking sector.

# Problem Statement 
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, retaining customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty. 
A bank is experiencing customer churn that is impacting overall customer satisfaction and revenue, as well as they lack insights into the factors influencing customer decisions to leave or stay with the bank. There is a need to proactively identify and address factors contributing to customer churn.

# Dataset Overview
The dataset contains information on 10,000 bank customers over six months. Each entry contains essential information like CustomerID, CreditScore, Geography, Gender, Tenure, Balance, and more.

## Data Dictionary
- CustomerId: Each customer has a specific identification called a CustomerId.
- Surname: This serves as the client's last name. It is a categorical variable.
- Credit Score: This is the customer's credit score, which measures their creditworthiness numerically. Since a customer with a better credit score is less likely to quit the bank, a higher credit score often implies a lower credit risk and can affect customer turnover.
- Geography: This feature indicates the country of residence of the customer.
- Gender: This feature represents the gender of the customer and can be either Male or Female.
- Age: The customer's age, in years.
- Tenure: The number of years that the consumer has been a bank client is shown by this characteristic.
- Balance: The balance shows how much money is in their bank account.
- NumOfProducts: This feature shows how many distinct banking products the client has with the bank. It accepts values between 1 and 4.
- HasCrCard: This variable indicates if the client has a credit card on file with the bank. The binary variable has the values 0 for "No" and 1 for "Yes."
- IsActiveMember: This feature indicates if the consumer is an active bank member. It's a binary variable once more, with 0 denoting "No" and 1 denoting "Yes."
- EstimatedSalary: This field contains data about the client's earnings.
- Churned: This variable tells us whether or not the consumer left (churned). The variable is binary, with 0 denoting "No" (the consumer stayed) and 1 denoting "Yes" (the customer left or "churned"). 

Data Source: [Hotel Dataset](https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/data)

# Project Objective 
The objective of the project is to give a clear understanding of customer demographics, behaviors, and churn patterns, identify key features influencing customer churn, and provide strategic recommendations for the bank based on data-driven insights.

# Key Performance Indicators (KPIs)
We also defined metrics and KPIs that will help answer the business questions. Examples include: <br>
- Total customers <br>
- Churn rate <br>
- % retained

# Data Cleaning 
Some steps taken during the data cleaning are as follows:
- The values 1 and 0 in the HasCrCard column were replaced with "Has CrCard" and "No CrCard" respectively. <br>
- The values 1 and 0 in the IsActiveMember column were replaced with "Active" and "Not Active" respectively. <br>
- The values 1 and 0 in the Churned column were replaced with "Churned" and "Retained" respectively. <br>
- A column titled Credit_Score_Group was created to group the credit score into; Poor (300 - 579); Fair (580 - 669); Good (670 - 739); Very Good (740 - 799) and Excellent (800 - 850).
- An Age_Group column was also created to group the ages into; Young Adult (20 - 39); Middle Adult (40 - 59) and Old Age (60+). <br>
- A Credit_Score_Sort and Age_Group_Sort columns were created on power query to use in sorting Credit_Score_Group and Age_Group when visualizing. 

## Dataset after cleaning
![Dataset after cleaning](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/6cc9de39-a65f-4b22-81df-3575bc4b6f3d)

# Visuals and Charts
The insights were represented using appropriate chart formats (e.g., donut charts and bar charts). For more in-depth information, interactive elements including slicer options were employed.

![Visual](https://github.com/Onorable-e/Customer-churn-analysis/assets/139487541/48169d6f-964b-4a60-9e23-61570ca52256)

# Insights
Some of the important insights and trends highlighted from the visuals created include:
- The churned rate is about 20.4%.
- Germany (39.92%) has the highest churn rate based on location. 
- Based on age group, middle age adults (40 - 59) have the highest churn rate.
- Customers with one distinct banking product have the highest churn rate of about 69.17% compared to customers with two, three, and four.
- About 898 and 1139 male and female customers respectively left (churned) the bank. 

# Recommendations
- The stakeholders should collect qualitative data using surveys to know specific reasons why customers are leaving.
- Also, the stakeholders could consider creating products that target those in the old age (60+) category to avoid losing them.
