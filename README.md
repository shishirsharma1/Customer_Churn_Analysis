# Customer Churn Analysis Dashboard
This project aims to analyze customer churn using Power BI. By transforming the data and creating insightful visualizations, we aim to identify key factors contributing to customer churn and provide actionable insights for improving customer retention.

## Understanding the Data
The dataset contains the following features:

**Customer_id**: Unique identifier for each customer.  
**Credit_score**: Customer’s credit score.  
**Country**: Country where the customer resides.  
**Gender**: Customer’s gender.  
**Age**: Customer’s age.  
**Tenure**: Duration of the customer’s relationship with the bank.  
**Balance**: Account balance of the customer.  
**Products_Number**: The product that the customer uses.  
**Credit_Card**: Whether the customer has a credit card (1 = Yes, 0 = No).  
**Active_Member**: Whether the customer is an active member (1 = Active, 0 = Inactive).  
**Estimated_Salary**: The estimated salary of the customer.  
**Churn**: Whether the customer has churned (1 = Churned, 0 = Active).  

## Step 1: Data Transformation
The following transformations were applied to clean and prepare the dataset:  

**Removed "estimated_salary"**: As account balance was deemed a better indicator for analysis.  
**Renamed and Reformatted Columns**: Changed column names and data types for easier analysis.  
**Removed "products_number"**: Replaced it with a more meaningful feature.  
**Modified "credit_card", "active_member", and "churn" statuses**: Standardized these values.  
**Grouped Age and Credit Score**: Created age groups (e.g., 21-30, 31-40) and credit score ranges.  
**Created Reference Columns**: Introduced new columns for age groups, account balance ranges, and credit score ranges to enhance visualizations.  
These steps ensured the data was clean, structured, and ready for analysis.  

## Step 2: Visualizations
After data preparation, the following visualizations were created using Power BI:  

**Churn Rate Overview**: Displays overall churn rate and trends over time.  
**Customer Segmentation**: Churn distribution by age groups, credit score ranges, and more.  
**Churn Indicators**: Analyzes key factors such as account balance, activity status, and credit card ownership in relation to churn.  
**Geographic Distribution**: Shows churn across different countries.  
These visualizations help identify the main drivers of customer churn and highlight opportunities for improvement in customer retention strategies.  
![image](https://github.com/user-attachments/assets/407e400d-a64d-4674-a410-76b8d83ac119)



## Tools Used
**Power BI**: For creating interactive dashboards.  
**Power Query**: For data cleaning and transformation.  
**DAX**: For creating calculated measures and metrics.  
