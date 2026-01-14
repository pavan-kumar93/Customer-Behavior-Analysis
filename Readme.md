Customer Behavior Data Analytics Project



\*\* Overview \*\*

This project analyzes customer shopping behavior using Python, SQL (PostgreSQL), and Power BI.

The goal is to clean and explore raw customer data, answer key business questions using SQL, and present insights through an interactive dashboard.



\*\* The project demonstrates end-to-end data analytics skills including:

Data loading and cleaning

Exploratory Data Analysis (EDA)

SQL querying for business insights

Dashboard creation and reporting



Dataset -

Source: Customer Shopping Behavior dataset (CSV)

Records: 3,900 customers



\*\* Key Columns:

Customer ID

Gender

Age Group

Category \& Item Purchased

Purchase Amount

Subscription Status

Discount Applied

Shipping Type

Review Rating

Previous Purchases



\*\* Tools \& Technologies \*\*

Python: Pandas, SQLAlchemy, Psycopg2

Database: PostgreSQL

Visualization: Power BI

Other: SQL, GitHub



Project Workflow / Steps

1\. Data Loading (Python)

Loaded CSV data using Pandas

Inspected structure, data types, and summary statistics



2\. Exploratory Data Analysis (EDA)

Reviewed distributions and categorical variables

Identified missing values and inconsistencies

Checked relationships between discounts and promotions



3\. Data Cleaning \& Feature Engineering

Filled missing review ratings using median per category

Renamed columns to snake\_case

Created a new feature: purchase\_frequency\_days

Removed redundant columns

Prepared clean data for database storage



4\. Load Data into PostgreSQL

Created a PostgreSQL database

Transferred cleaned dataset from Python to PostgreSQL using SQLAlchemy



5\. SQL Analysis

Answered real-world business questions using SQL queries

Analyzed revenue, discounts, subscriptions, and customer segments



6\. Power BI Dashboard

Built an interactive dashboard to visualize:

Customer distribution

Revenue \& sales by category

Age group analysis

Subscription behavior

Average ratings



\*\* Results \& Insights \*\*

Insights from Power BI Dashboard

* Clothing is the top-performing category, generating the highest revenue and sales volume
* Young Adults contribute the largest share of total revenue
* Footwear has the highest average customer rating compared to other categories



Insights from SQL Analysis

* Majority of customers are non-subscribers, indicating low subscription adoption.
* Loyal customers form the largest segment, while new customer acquisition is limited.
* Average spend is similar for subscribed and non-subscribed customers, suggesting subscriptions drive retention more than higher spending.
* Non-subscribed customers generate most revenue due to higher customer volume.
* Young adult customers generate the highest total revenue, slightly outperforming other age groups, indicating this segment as the strongest revenue contributor.



👤 Author

\*\*Pavan Kumar\*\*

Aspiring Data Analyst

---

\*\* Feedback \*\*

If you find this project useful, feel free to ⭐ the repository or share your feedback.



\*\* Acknowledgement \*\*

This project is created for learning and portfolio purposes, inspired by online tutorials and publicly available datasets.



