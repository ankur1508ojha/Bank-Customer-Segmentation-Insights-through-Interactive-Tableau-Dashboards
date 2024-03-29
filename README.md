# Bank Customer Segmentation: Insights through Interactive Tableau Dashboards 
# Description:

# This project involves the analysis and segmentation of bank customer data to tailor sales strategies using advanced analytics. We've harnessed the power of AWS services, Apache Airflow, Fivetran, Snowflake Data Warehouse, and Tableau to achieve end-to-end data processing, storage, visualization, and insight extraction.

# Table of Contents
  Installation
  AWS Account with configured CLI.
  Apache Airflow installed and set up.
  Fivetran & Snowflake accounts.
  Tableau Desktop or Tableau Server.

# Setup AWS Services:
  Configure S3 for data storage.
  Set up EC2 instances for data processing.
  Use RDS for relational data management.
  Usage

Data Acquisition: Collect raw bank customer data.
Data Storage in AWS S3: Store the raw datasets into AWS S3 buckets.
Data Processing on AWS EC2: Initiate transformation processes.
Manage Data on AWS RDS: Store structured bank data.
Orchestrate with Apache Airflow: Manage and monitor the data flow.
Integrate Data with Fivetran: Handle the ETL processes.
Centralize Data in Snowflake: Create a unified repository for analytics.
Visualize Data with Tableau: Present the processed data in an understandable format.
Implement Filters in Tableau: Enhance dashboard interactivity.
Gain Insights: Analyze visual data to form actionable strategies.

<img width="662" alt="Screenshot 2024-01-18 at 6 55 26 PM" src="https://github.com/ankur1508ojha/Bank-Customer-Segmentation-Insights-through-Interactive-Tableau-Dashboards/assets/102976689/44fced4d-dba8-43d1-95fd-beca9bb932d0">





# Tableau_Story
**Summary of the key insights and findings from the analysis. The conclusions include recommendations for improving sales performance, such as focusing on the top-performing products, regions, and customer segments.
**

The purpose of this project is to analyze a dummy dataset for an imaginary bank in the United Kingdom. 

**Data Source:**
The dataset consists of Customer ID, Trx ID , Name, Surname, Gender, Age, Region, Job Classification, Date Joined, and Balance.
Job Classification: White collar, Blue collar, and other.
Date Joined: Customers joined from January to December 2015.
Balance: Amount of money on the customer's account.

**Data Process**:
To compare regions, the data is grouped into 4 regions of England, Northern Ireland, Scotland, and Wales.
These regions will be used as filters for other attributes.
The data is distributed by balance, age, gender, and job classification.

**Customer Baseline:**

Dashboard | United Kingdom: The major customers in the United Kingdom are around 30-40 years old, which is about 50% of the entire customer base. 54% of the customers are male and 46% are female. White-collar customers are more prevalent in the UK than blue-collar or other job classifications.

Dashboard | England: In England, 70% of the customers are white-collar workers.

Dashboard | Scotland: Customers in Scotland are predominantly males in their late 40s and early 50s. The representation of white-collar workers is extremely low, only 7%.

Dashboard | Wales: The data for Wales shows an above-average representation of mid-size balances.
Dashboard | Northern Ireland: Northern Ireland is mostly represented by female customers in younger age groups than any other region.
