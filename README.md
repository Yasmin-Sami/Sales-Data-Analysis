# Sales-Data-Analysis
Interactive sales dashboard using Excel showing trends, returns, and top products.

## 🛠️ Tools Used
- Excel

## 🧹 Data Cleaning
1. **Remove Duplicates**: Eliminated duplicate values from the dataset.
2. **Format Modification**: Adjusted data formats for numbers and dates.
3. **Correcting Data Types**: Ensured proper aggregation and analysis.
4. **Filtering Irrelevant Data**: Focused on meaningful insights.

These cleaning steps improved the reliability of the dashboard and ensured that all insights were based on clean, trustworthy data.

## ?? Data Merging
In this project, I merged multiple datasets to create a comprehensive sales view. The data sources included:

- **Customers table** – containing client details  
- **Orders table** – listing transaction details  
- **Products table** – including product information

Using **Customer ID** and **Product ID** as keys:

- Joined the orders table with the customers table to link each order to a specific client.
- Joined the orders table with the products table to connect each order to its product details.
- Ensured data consistency by checking for unmatched values and missing keys.
- Used **Power Query (in Excel)** for structured and efficient merging.

This merge enabled a full view of who bought what, when, and where — forming the foundation of the dashboard analysis.

## 📈 Analysis

### 🔍 Key Highlights:
- **Total revenue**: EGP 14,472,200
- **Total number of products**: 14
- **Total number of orders**: 3,473
- **Number of clients**: 964
- **Active cities**: 14

## 📊 Visualizations

### 🏙️ Top 10 Best-Selling Cities:
Horizontal bar chart showing top-performing cities by revenue.

### 📦 Sales by Product Type:
Combined bar chart displaying total sales and quantity sold for products such as ties, jeans, and bags. Ties and jeans generate the highest revenue.

### 📅 Daily and Monthly Sales Trends:
Line charts track daily fluctuations and monthly trends in sales. Highest monthly sales recorded in June (EGP 4.2M), with a declining trend towards December.

### 🌍 Sales by Country:
Pie chart indicating **KSA** as the top contributor (35%), followed by **Syria** (24%) and **UAE** (18%).

### 🔄 Top 5 Returned Products:
Donut chart showing returns, with **Jeans**, **T-shirts**, and **Bags** being the most returned items.

### 🧾 Number of Orders Per Product:
Bar chart presenting product-wise order volume, highlighting **Jeans** and **Ties** as the most frequently ordered items.

### Report :
![Sales Analysis Dashboard](https://github.com/user-attachments/assets/f6816515-5e3a-4344-b650-2aea1e64ad2a)

