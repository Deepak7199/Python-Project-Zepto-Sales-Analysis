🛒 Zepto Sales & Products Data Analysis

📌 Project Overview
This project performs an in-depth exploratory data analysis (EDA) on sales and product data from Zepto, a rapid grocery delivery service. The goal is to uncover business insights regarding sales trends, product performance, delivery efficiency across various cities, and customer purchasing behaviors using Python's powerful data analysis and visualization libraries.

🛠️ Tools & Technologies Used
Data Manipulation & Cleaning: pandas, numpy

Data Visualization: matplotlib, seaborn

Environment: Jupyter Notebook

📂 Dataset Information
The analysis is based on two primary datasets:

zepto_products.csv: Contains inventory details (38 unique products).

product_id, product_name, category, base_price

Categories include: Fruits & Vegetables, Dairy & Eggs, Personal Care, Household Essentials, Beverages, and Munchies.

zepto_sales.csv: Contains over 220,000 transaction records for the year 2024.

order_id, order_date, product_id, quantity, city, delivery_status, customer_id, delivery_time_mins, total_amount

🧹 Data Cleaning & Preprocessing
To ensure data quality and accuracy, the following data cleaning steps were executed using Pandas and NumPy:

Handling Missing Values: Dropped rows with null values in city and delivery_status. Imputed missing values in delivery_time_mins using the overall mean delivery time (~26 mins).

Removing Duplicates: Identified and dropped 216 duplicate order records.

Data Type Conversion: Converted the order_date column from an object (string) data type to a proper datetime format for time-series analysis.

📊 Exploratory Data Analysis (EDA)
The project explores the data through various aggregations and visualizations:

Top Performing Products: Bar charts displaying the top 5 products generating the highest revenue.

City-wise Sales Distribution: Analyzed total sales volume across major Indian cities (Mumbai, Bangalore, Delhi, Hyderabad, Pune, etc.).

Delivery Time Analytics: Calculated and compared average delivery times across different cities.

Monthly Sales Trends: Tracked revenue generation over the 12 months of 2024 to identify peak sales periods.

Category Insights: Grouped sales data by product category to determine which segments drive the most revenue.

💡 Key Insights
Top Cities: Mumbai and Bangalore generated the highest sales revenue by a significant margin.

Top Revenue Categories: Personal Care and Dairy & Eggs emerged as the highest-grossing categories.

Bestselling Products: Non-grocery items like Handwash, Detergent 1kg, and Toilet Paper, along with Paneer 200g, dominated the total sales volume.

Delivery Efficiency: The average delivery time across all orders and cities remained highly consistent at roughly 26 minutes.

🚀 How to Run the Project
Clone this repository:

Bash
git clone https://github.com/yourusername/zepto-data-analysis.git
Navigate to the project directory:

Bash
cd zepto-data-analysis
Install the required dependencies:

Bash
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook to view the code and visualizations:

Bash
jupyter notebook project_code.ipynb
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

✨ Author
Deepak Shukla * GitHub: @yourusername

LinkedIn: Your LinkedIn Profile
