# Amazon Sales & Profitability Analytics Dashboard

## 📊 Project Overview
This project involves a comprehensive analysis of Amazon sales data to identify key drivers of profitability. The primary objective was
 to evaluate the impact of **Discount Strategies** and **Payment Methods** on the bottom line.

## 🛠️ Tech Stack & Skills
- **Data Visualization:** Power BI / Excel
- **Data Transformation:** Power Query
- **Analytical Calculations:** DAX (Data Analysis Expressions)
- **Version Control:** Git & GitHub

## 💡 Strategic Business Insights
1. **The Discount Threshold:** Analysis reveals a negative correlation between high discounts and net profit. Discounts exceeding
 **5%** result in a significant margin drop, indicating that the volume increase does not compensate for the price reduction.
2. **Payment Efficiency:** While **UPI and Wallets** dominate in transaction frequency, **Credit Cards** yield the highest average order value (AOV).
3. **Product Health:** Cross-referencing ratings with review counts identified "High-Volume/Low-Rating" products that require immediate quality intervention.

## 📐 Key Metrics (DAX Logic)
- **Profit Margin %**: `(Total Profit / Total Revenue) * 100`
- **Customer Sentiment Index**: A weighted average of Ratings and Review Counts.

## 🚀 Repository Structure
- `/Data`: Contains the raw and cleaned datasets.
- `Amazon_Sales_Analysis.pbip`: The source Power BI file.