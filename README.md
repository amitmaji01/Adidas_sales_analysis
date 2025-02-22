
# Adidas Sales Analysis - Power BI Dashboard

## 📌 Project Overview
This project is a **Power BI Sales Analysis Dashboard** for **Adidas** that provides insightful visualizations on sales trends, product performance, and key business metrics. The dashboard helps analyze total revenue, profit margins, units sold, and sales distribution across various dimensions.

## 🔍 Key Features
- **Total Sales, Profit Margin %, and Units Sold Overview**
- **Sales Analysis by Day, Region, and Product Category**
- **Comparison of Online, Outlet, and In-Store Sales**
- **Cumulative Sales Trend Analysis**
- **Product Categorization Based on Price Range**
- **Dynamic Filtering for Enhanced Insights**

## 🛠 Data Processing & Transformation
### ✅ Data Cleaning Steps:
1. **Removed Dollar Signs ($) & Converted to Numeric**
2. **Converted "Invoice Date" to Proper Date Format**
   - Used "Change Type with Locale" to ensure correct date format
3. **Handled Missing Values in "Price per Unit"**
4. **Ensured "Units Sold" is a Numeric Column**
5. **Extracted Day Name from Date for Sales Analysis**

### ✅ DAX Measures Used:
- **Profit Margin %:**
  ```DAX
  Profit Margin % = DIVIDE( SUM('Adidas_Sale'[Operating Profit]), SUM('Adidas_Sale'[Total Sales]) ) * 100
  ```
- **Total Sales Calculation:**
  ```DAX
  Total_Sale = SUM('Adidas_Sale'[Units Sold] * 'Adidas_Sale'[Price per Unit])
  ```
- **Cumulative Sales for Trend Analysis**

## 📊 Visualizations Used
- **KPI Cards** for Total Sales, Profit Margin %, and Units Sold
- **Bar Charts** for Sales by Quarter, Sales Method, and Day-wise Trends
- **Pie Charts** for Sales Distribution
- **Treemap** for Units Sold by Product
- **Line Graph** for Cumulative Sales & Profit Trends

## 📁 Dataset
The dataset contains sales transaction details, including:
- **Invoice Date**
- **Product Category**
- **Units Sold**
- **Price per Unit**
- **Total Sales**
- **Operating Profit**

## 🚀 How to Use
1. **Open the Power BI File (.pbix)**
2. **Connect to the Adidas Sales Dataset (.csv)**
3. **Refresh the Data** to see real-time changes
4. **Interact with Filters & Visualizations** for insights

## 🔗 Connect With Me
I’m currently learning **Power BI and DAX** and implementing it through projects. Connect with me on **[LinkedIn](https://www.linkedin.com/in/amit-maji-a421671bb/)** for discussions and collaboration! 🚀

💡 **Feedback & Suggestions are Welcome!**

#PowerBI #DataAnalytics #SalesAnalysis #DataVisualization #DAX #DashboardDevelopment

