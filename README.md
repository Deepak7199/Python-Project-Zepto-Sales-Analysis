🛒 Zepto Sales & Products Data Analysis

📌 Project Overview
This project performs an in-depth exploratory data analysis (EDA) on sales and product data from Zepto, a rapid grocery delivery service. The goal is to uncover business insights regarding sales trends, product performance, delivery efficiency across various cities, and customer purchasing behaviors using Python's powerful data analysis and visualization libraries.

<img width="1104" height="889" alt="image" src="https://github.com/user-attachments/assets/d5112c92-67a8-478c-87ed-ade8368adc87" />



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

<img width="606" height="647" alt="image" src="https://github.com/user-attachments/assets/a57b5f68-40f5-41ef-9ca3-2826241f3d6f" />


🧹 Data Cleaning & Preprocessing
To ensure data quality and accuracy, the following data cleaning steps were executed using Pandas and NumPy:

Handling Missing Values: Dropped rows with null values in city and delivery_status. Imputed missing values in delivery_time_mins using the overall mean delivery time (~26 mins).

<img width="455" height="876" alt="image" src="https://github.com/user-attachments/assets/b5db5848-1604-4752-9b2c-bd019022b609" />

Removing Duplicates: Identified and dropped 216 duplicate order records.

<img width="368" height="465" alt="image" src="https://github.com/user-attachments/assets/f0198c8f-4f1c-46b6-ba09-d9c6e4f92ae0" />


Data Type Conversion: Converted the order_date column from an object (string) data type to a proper datetime format for time-series analysis.

<img width="652" height="272" alt="image" src="https://github.com/user-attachments/assets/f9c61024-c519-4e51-ab00-9dd5081b8c1b" />


📊 Exploratory Data Analysis (EDA)
The project explores the data through various aggregations and visualizations:

Top Performing Products: Bar charts displaying the top 5 products generating the highest revenue.

<img width="1107" height="790" alt="image" src="https://github.com/user-attachments/assets/d0b43bfd-6528-4fa7-a5e1-9a68f828abab" />


City-wise Sales Distribution: Analyzed total sales volume across major Indian cities (Mumbai, Bangalore, Delhi, Hyderabad, Pune, etc.).

<img width="1094" height="779" alt="image" src="https://github.com/user-attachments/assets/d9e5893c-2ddb-4e4d-9bcd-64c53820e525" />


Delivery Time Analytics: Calculated and compared average delivery times across different cities.

<img width="1103" height="867" alt="image" src="https://github.com/user-attachments/assets/09983ecd-7ac2-42c2-a8d1-b3af5d2cfa87" />


Monthly Sales Trends: Tracked revenue generation over the 12 months of 2024 to identify peak sales periods.

<img width="877" height="692" alt="image" src="https://github.com/user-attachments/assets/1023a2a0-1e3b-4262-a0b1-99caf1e73c83" />

Category Insights: Grouped sales data by product category to determine which segments drive the most revenue.

<img width="893" height="676" alt="image" src="https://github.com/user-attachments/assets/9bb8b579-7612-4e90-8174-6f763d285566" />


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
Deepak Shukla * GitHub: @Deepak7199

LinkedIn:https://www.linkedin.com/in/deepak-shukla-30b6492a9/
