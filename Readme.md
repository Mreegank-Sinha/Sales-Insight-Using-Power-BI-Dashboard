# Sales Insight Using Power BI Dashboard

![image](https://github.com/user-attachments/assets/a0c14888-6723-42bc-ac2e-5cb6b4d9b5c5)

## Overview
This project focuses on generating sales insights using data analysis techniques to help businesses make data-driven decisions. The project is designed for individuals aspiring to become data analysts or data scientists, offering hands-on experience in executing a real-world data analysis project similar to those in corporate environments.

The primary objective of this project is to demonstrate the end-to-end process of solving business problems using data analytics. Unlike conventional tutorials that only focus on using tools like Power BI or Tableau, this project emphasizes the entire workflow, from problem identification to solution implementation.

The project is broken down into multiple stages, covering:

- Understanding the business problem

- Data discovery and exploration

- Data cleaning and preprocessing

- Building insightful visualizations in Power BI

- Stakeholder feedback and iterative improvements

By the end of this project, a comprehensive Power BI dashboard will be created, providing actionable insights into sales performance. Additionally, participants will act as stakeholders to provide feedback, simulating real-world corporate interactions where data analysts refine their work based on user input.

## Problem Statement

### Business Context:
AtliQ Hardware, a computer hardware and peripherals supplier, provides products to various clients, including Excel Stores across India. The company has its headquarters in Delhi and multiple regional offices across the country. The Sales Director, is facing significant challenges in tracking and understanding sales trends in a dynamically evolving market.

Challenges:

1. Lack of Centralized Insights: The sales data is fragmented across multiple Excel files, making it difficult for the sales director to get a holistic view of sales performance.

2. Subjective Reporting: Regional managers provide verbal updates on sales trends, which often include biases or sugar-coated versions of the actual situation.

3. Time-Consuming Data Retrieval: Extracting meaningful insights from numerous spreadsheets is inefficient and prone to errors.

4. Data-Driven Decision Making: Without an intuitive visualization tool, making strategic decisions regarding promotions and sales strategies is challenging.

### Proposed Solution:
To address these challenges, the project aims to create a Power BI dashboard that provides:

- A centralized view of revenue trends and sales performance.

- Region-wise and product-wise breakdowns of sales data.

- Year-over-year comparisons to track growth and decline.

- Automated reports and alerts, reducing reliance on manual reporting.

With this dashboard, we can easily track key performance metrics, gain real-time insights, and make informed business decisions without relying on verbal reports from regional managers. This project not only enhances sales tracking but also fosters a data-driven culture within the company.

## Dataset
The dataset is a sales transactions database from AtliQ Hardware, containing various relational tables. It includes information about customers, transactions, products, markets, and dates. The transactions table is the primary source of sales data, storing details such as product codes, customer codes, market codes, order dates, sales amounts, and currencies. Other tables, like the customers table, list client details, while the markets table specifies the business regions. The dataset also includes inconsistencies such as negative sales values and different currencies (INR & USD), requiring data cleaning. It contains 150,000+ transactions and supports SQL-based analysis for business insights.

## EDA
Exploratory Data Analysis (EDA) is a crucial step in understanding the dataset before performing transformations and modeling. In this project, we conducted EDA to identify patterns, anomalies, and data quality issues. Below are the key steps we followed:

1️. Understanding the Dataset
- Loaded the dataset into Power BI and SQL for preliminary analysis.
- Examined the schema, column data types, and missing values.

2️. Handling Duplicates and Data Quality Issues
- Identified duplicate transactions using Power Query transformations.

  <img width="870" alt="Duplicate Values" src="https://github.com/user-attachments/assets/e370f501-14c2-46c4-9b6e-7c3a14712eeb" />

- Detected and resolved currency inconsistencies (e.g., "INR" vs. "INR/r") using Power Query transformations.

  <img width="870" alt="Duplicate Values" src="https://github.com/user-attachments/assets/0d4edf23-f9ac-4477-a3b3-95c08a0b5938" />

- Removed or corrected records with erroneous sales amounts (e.g., negative or zero values).

## Procedure
### Step 1. Creating Relationships & Data Model
- Selecting the Model View in Power BI.
- Identifying relationships between tables (e.g., transactions, customers, and products).

<img width="801" alt="Star Schema" src="https://github.com/user-attachments/assets/0d96c905-88a7-45f2-b116-4233e8607b73" />

### Step 2. Creating New Table for Analysis
- Creating a table named BaseMeasures for further analysis.
- Creating a new measure for total revenue of tansactions.
- Creating another measure for total sales quantity.

![image](https://github.com/user-attachments/assets/112fc203-bc28-43da-ab3a-830ce9f4070c)

### Step 3. Creating Cards, Graphs and other Insights Cards
- In order to fulfill our primary objective we are going to make multiple cards and graphs which can be used for insight.
- Revenue Card

![image](https://github.com/user-attachments/assets/de182d2b-6c59-40d3-860f-b1487d0a976e)

- Sales Quantity Card

![image](https://github.com/user-attachments/assets/3e13d2de-05f8-4f63-8105-048e4e0225cf)

- Revenue by Markets/Zones

![image](https://github.com/user-attachments/assets/bc176604-75f1-43c6-b98d-9b1cee35d92b)

- Sales Quantity by Markets/Zones

![image](https://github.com/user-attachments/assets/6f2a1b0f-35f6-4423-aabe-13044e5ba4e7)

- Year and Month Sliders/Buttons for Insights by Date

<img width="611" alt="image" src="https://github.com/user-attachments/assets/54e30755-e2c3-414c-9392-f63d0ad518a9" />

- Top 5 Customers and Top 5 Products

![image](https://github.com/user-attachments/assets/3b4f1f6f-1c03-42ee-8089-a94876fabee1)

- Revenue Graph

![image](https://github.com/user-attachments/assets/73b83cd4-3cb0-4052-b44b-8099b44643b8)

# Conclusion

Utilising PowerBi and SQL, we were able to create a relevant Dashboard which can resolve our problem of lack of valuable Insights.
