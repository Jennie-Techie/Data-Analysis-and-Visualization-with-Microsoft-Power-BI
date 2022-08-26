# Data-Analysis-and-Visualization-with-Microsoft-Power-BI

## PROJECT DESCRIPTION
This is a data analysis project which is centered around business KPIS, data cleaning and transformation, data visualization. 

#### Data Source
* CSV files / Excel Workbook

#### Tools
* Power BI Desktop

#### This project was built with the following Power BI Desktop components:
* **Power Query**
* **Power Pivot**
* **Power View**

## Business Requirements & User Stories
The table below shows the business requirements and user stories, derived after meeting the various stakeholders. 


|User Story no. | As a (role) | I want (goal) | so that (result) | Acceptance Criteria |
|-------------- | ------------| --------------| -----------------| -------------------|
| 1.            | **Sales Executive** | To see at a glance our sales performance and revenue across various states | Can evaluate our profitability and plan towards the next quarter | A power BI dashboard which tracks sales KPIs and updates daily |
| 2.            | **Sales Manager** | To know our best and least performing products in the market | Can strategize on how to improve the sales of the low performing products | A Power BI dashboard with filters on products data |
| 3. | **HR Manager** | A detailed overview of our sales team’s performance | Can determine promotions and bonuses in the next quarter | A Power BI dashboard with filters on sales representatives and their performance |
| 4. | **Sales Representative** | An overview of our sales per customer | Can track my customers and device ways to keep them loyal to our brand | A Power BI dashboard with filters on customer data and updates daily |



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


