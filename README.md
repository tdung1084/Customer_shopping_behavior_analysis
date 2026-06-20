# Customer Behavior Data Analyst Portfolio Project

This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.

**Dataset**

Dataset Size
3,900 records
18 columns

Key Features
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
Shopping behavior (Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)

Data Quality
37 missing values in the Review Rating column
Missing values were imputed using category-level median ratings

**Project Workflow**
1. Data Preparation & Cleaning
Loaded data using Pandas
Performed initial exploration using df.info() and df.describe()
Handled missing values in review ratings
Standardized column names using snake_case
Removed redundant columns
Validated data consistency

2. Feature Engineering
Created age_group categories
Generated purchase frequency metrics
Prepared analytical fields for segmentation

3. SQL Analysis
Key business questions answered:
Revenue by Gender
High-Spending Discount Users
Top 5 Products by Rating
Shipping Type Comparison
Subscribers vs Non-Subscribers
Discount-Dependent Products
Customer Segmentation
Top 3 Products per Category
Repeat Buyers & Subscription Analysis
Revenue by Age Group

4. Dashboard Development
Built an interactive Power BI dashboard featuring:
Revenue KPIs
Customer demographics
Product performance
Subscription insights
Customer segmentation
Age-group analysis
Shipping and discount trends

5. Reporting & Presentation
Created a detailed business report
Designed a presentation 
Summarized findings and recommendations for stakeholders

**Dashboard Highlights**
The dashboard enables users to:
Monitor overall sales performance
Compare subscriber and non-subscriber behavior
Analyze customer demographics
Identify top-performing products
Track customer loyalty and repeat purchases
Evaluate discount effectiveness

**Results & Insights**
Key Findings
Customer spending varies across demographic groups.
Subscribers generate higher long-term value.
Certain products rely heavily on discount-driven sales.
Loyal customers contribute significantly to revenue.
Product ratings help identify high-performing items.

Business Recommendations
Promote subscription benefits to increase retention.
Implement loyalty programs for repeat customers.
Optimize discount strategies to protect profit margins.
Highlight top-rated products in marketing campaigns.

## How to Run
### 1. Clone the Repository
```bash
git clone https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI.git
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

### 2. Open the Python Notebook
Open the `Customer_Shopping_Behavior_Analysis.ipynb` notebook.
This notebook contains:
* Data Import
* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Data Validation
* Connection to SQL Database
* Loading the cleaned dataset into PostgreSQL / MySQL / SQL Server

### 3. Create and Load the Database
1. Create a database in PostgreSQL, MySQL, or SQL Server.
2. Configure the database connection in the Python notebook.
3. Run the notebook cells to load the cleaned dataset into the SQL database.

### 4. Run SQL Analysis
Open the `customer_behavior_sql_queries.sql` file.
Execute the SQL queries to answer key business questions, including:
* Revenue by Gender
* Subscriber vs Non-Subscriber Analysis
* Customer Segmentation
* Product Performance Analysis
* Revenue by Age Group
* Discount Impact Analysis

### 5. Build the Power BI Dashboard
1. Open `customer_behavior_dashboard.pbix`.
2. Connect Power BI to the SQL database.
3. Refresh the data connection.
4. Explore the interactive dashboard and business insights.

### 6. Create Report and Presentation
* Prepare the project report summarizing methodology, findings, and recommendations.
* Build the presentation deck using Gamma AI.
* Present key insights, dashboard highlights, and business recommendations.
