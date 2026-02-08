# **Analysis of Medical Insurance Expenses Using Demographic and Lifestyle Factors in Power BI**

## Chapter 1 Introduction

#### 1.1 Background of the Study
Healthcare and medical insurance costs have increased significantly over the past decade due to lifestyle changes, aging populations, and chronic diseases. Insurance companies and healthcare providers require data-driven insights to understand cost-driving factors and manage risks effectively. Traditional analysis methods often fail to uncover hidden patterns in large datasets. Business Intelligence (BI) tools such as Microsoft Power BI enable interactive data exploration and visualization, supporting informed decision-making.

#### 1.2 Problem Statement
Medical insurance expenses vary widely among individuals due to demographic and lifestyle factors. However, identifying the key contributors to high medical costs remains a challenge. Without proper analysis, insurers may misprice premiums and healthcare providers may fail to design preventive strategies.

#### 1.3 Objectives of the Project
•	To analyze medical insurance expenses using demographic and lifestyle data
•	To identify major factors influencing healthcare costs
•	To compare expenses across regions, gender, and smoking status
•	To develop interactive dashboards using Power BI for decision support

#### 1.4 Scope of the Project
This project focuses on exploratory and descriptive analysis of insurance data using Power BI. Predictive modeling is outside the core scope but may be considered as future work.

#### 1.5 Significance of the Study
The project provides valuable insights for insurance companies, healthcare planners, and policymakers by highlighting cost drivers and high-risk groups. It also demonstrates the practical application of Power BI in healthcare analytics.

## Chapter 2: Literature Review

Several studies highlight smoking, obesity, and age as major contributors to increased medical expenses. Previous research emphasizes the role of data visualization and BI tools in healthcare analytics for monitoring trends and supporting strategic planning. Power BI has been widely adopted due to its ease of use, real-time interactivity, and advanced visualization capabilities.

## Chapter 3: Methodology

#### 3.1 Dataset Description
The dataset consists of individual medical insurance records with the following attributes: - Region - Smoker status - Sex - Age - Number of children - Body Mass Index (BMI) - Medical expenses (target variable)

#### 3.2 Tools and Technologies
•	Microsoft Power BI Desktop
•	Power Query Editor
•	DAX (Data Analysis Expressions)

#### 3.3 Data Collection
The dataset was obtained from a publicly available insurance dataset commonly used for healthcare cost analysis and educational purposes.

#### 3.4 Data Preprocessing
•	Removal of inconsistencies and formatting issues
•	Conversion of variables into appropriate data types
•	Handling categorical variables
•	Creation of age groups and BMI categories for better analysis

#### 3.5 Data Modeling
A single-table data model was used. Calculated measures were created using DAX to compute total, average, and segmented expenses.

#### 3.6 Data Analysis Approach
Exploratory Data Analysis (EDA) was conducted using visual analytics to identify patterns, trends, and relationships between variables.

## Chapter 4: System Implementation

#### 4.1 Dashboard Design
The Power BI dashboard includes: - KPI cards showing total and average expenses - Bar charts for expenses by region, gender, and smoking status - Line charts showing expense trends with age - Scatter plots illustrating BMI versus expenses - Interactive slicers for filtering data

#### 4.2 DAX Measures
Key DAX measures were created to calculate: - Total Medical Expenses - Average Expenses per Individual - Expenses by Smoker Status - Regional Expense Distribution

## Chapter 5:  Results and Analysis

#### 5.1 Key Findings
•	Smokers incur significantly higher medical expenses compared to non-smokers
•	Medical expenses increase with age
•	Higher BMI is associated with increased healthcare costs
•	Regional differences exist in average medical expenses
•	Gender has a relatively smaller impact compared to lifestyle factors

#### 5.2 Dashboard Insights
Interactive dashboards allow users to filter and analyze data dynamically, providing clear insights into high-risk groups and cost patterns.

## Chapter 6: Conclusion
This project successfully demonstrates how Power BI can be used to analyze healthcare insurance data and extract meaningful insights. The findings highlight smoking status, BMI, and age as dominant factors influencing medical expenses. The developed dashboards support effective decision-making for healthcare and insurance stakeholders.

## Chapter 7: Future Work
•	Integration of machine learning models for expense prediction
•	Inclusion of additional clinical variables
•	Real-time data integration
•	Deployment of dashboards to Power BI Service

## References
1.	Healthcare Cost Analysis Datasets
2.	Microsoft Power BI Documentation
3.	Studies on Lifestyle Factors and Medical Expenses
