# customer_shopping_behavior_analysis

🔍 Overview

This project focuses on analyzing customer shopping behavior using transactional data. The goal is to uncover insights into customer spending patterns, product preferences, and business performance to support data-driven decision-making.

The workflow includes data processing in Python, querying in MySQL, and visualization using Power BI.

📁 Dataset

Total Records: 3,900

Features: 18 columns

Key Information:

Customer demographics (Age, Gender, Location)<br>
Purchase details (Product, Category, Amount, Season)<br>
Behavioral data (Discount usage, Purchase frequency, Ratings, Shipping type)<br>
Data Issues:<br>
Missing values in the Review Rating column<br>
Some redundant columns (e.g., promo code usage)<br>

🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & EDA<br>
MySQL – Data querying & analysis<br>
Power BI – Dashboard & visualization<br>
Jupyter Notebook – Development environment<br>

⚙️ Project Steps

1. Data Loading & Exploration<br>
Loaded dataset using Pandas<br>
Used .info() and .describe() for initial analysis<br>

3. Data Cleaning<br>
Handled missing values using median imputation<br>
Renamed columns for consistency (snake_case)<br>
Removed redundant columns<br>

4. Feature Engineering<br>
Created age groups from customer age<br>
Converted purchase frequency into numerical format<br>

5. SQL Analysis (MySQL)<br>
Performed business-focused queries such as:<br>
Revenue by gender<br>
Top-rated products<br>
Customer segmentation (New, Returning, Loyal)<br>
Subscribers vs non-subscribers analysis<br>
Discount impact on purchases<br>

7. Data Visualization<br>
Built an interactive Power BI dashboard<br>
Visualized key KPIs like revenue, customer segments, and product performance<br>

📊 Dashboard

The Power BI dashboard includes:<br>
Revenue breakdown (by gender, age group, category)<br>
Customer segmentation insights<br>
Top-performing products<br>
Discount and subscription analysis<br>

📈 Results & Insights

Identified high-value customer segments<br>
Found top-performing and highly rated products<br>
Observed impact of discounts on sales behavior<br>
Highlighted differences between subscribers and non-subscribers<br>

🚀 How to Run

Clone the repository<br>

git clone <your-repo-link>
cd project-folder

Install dependencies<br>

pip install pandas numpy mysql-connector-python

Run Python scripts / Jupyter Notebook<br>
Perform data cleaning and EDA<br>
Connect to MySQL<br>
Import cleaned dataset<br>
Run SQL queries<br>
Open Power BI file<br>
Load dataset<br>
Explore dashboard<br>

📌 Key Takeaways

This project demonstrates end-to-end data analysis skills including:<br>

Data cleaning and preprocessing<br>
SQL-based business analysis<br>
Data visualization and storytelling<br>
