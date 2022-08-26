# Data-Analysis-and-Visualization-with-Microsoft-Power-BI

## PROJECT DESCRIPTION

## Business Requests & User Stories
Read the business requirements and user stories to understand the problems to be solved with data analysis and possible solution to be considered. 

## Business Problem
 The sales executive would like to see how the sales department have performed since the new sales manager joined the company two years ago, in order to determine promotions and bonuses. He wants the dashbaord to be in the company's brand colors: white and blue. The data to be used for the dashboards reside in the company's Mysql database and some excel files. 


#### Business Questions
* How many customers have we served in the past 2 years? 
* What is our total revenue in the past 2 years? 
* What is our profit for each year? 
* What is our profit percentage per year. 
* Who are our top sales representatives?  
* How have sales been distributed across various states?
* Who are our top 5 customers?

#### Key Metrics / Key Performance Indicators
* Total Revenue per year
* Total number of customers
* Total cost per year
* Profit
* Profit percentage per year
* Top 5 selling products
* Top 5 performing sales representatives
* Total sales per month

### Data Source
* CSV files

#### Tools
* Power BI Desktop
#### This project was built with the following Power BI Desktop components:
* **Power Query**
* **Power Pivot**
* **Power View**


# PROJECT PROCEDURES

### Power BI Desktop
Launch Power BI Desktop. Import Data

### ETL with Power Query: 
* Import Data to Power Query; Power BI's built in Extraction-Transform-Load tool. 
* Explore the data to see what tables contain columns that need to be cleaned. 
* Identified 3 tables which need to be transformed: Sales Table, Employee Table, Products Table.

#### Data Cleaning of Sales Table
> * Set 1st row as header
> * Remove unnecessary columns
> * Rename Address 1
> * Extract the state from the address 2.
> * Format the date from text to date type
> * Extract the month and Year from the date column
> * Format numbers: change the number type from text to whole numbers

#### Data Cleaning of Employee Table
> * Capitalize the first letters of the first and last names of employees
> * Change salary column data type to whole numbers

#### Data Cleaning of Products Table
> * Change data type of cost price column to whole number
> * Change data type of selling price column to whole number

#### Merge Tables
> * Merge Product table and Sales table using Product column

#### Close and Apply Changes in Power Query

### CREATE DATA MODELS
* Check data models to ensure tables are properly linked. 
* Link Sales persons in both Employee table and Sales table.

### POWER PIVOT: CREATE MEASURES IN DAX
Create the following measures:
> * Total Customers
> * Profit
> * Profit Percentage

### CREATE VISUALS 
* Insert charts, cards, filters and slicers to show all the KPIs. 
* Format dashbaord background

### PUBLISH & SHARE


