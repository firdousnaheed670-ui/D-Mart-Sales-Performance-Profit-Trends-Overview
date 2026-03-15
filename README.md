# D-Mart-Sales-Performance-Profit-Trends-Overview
Power BI project analyzing D-Mart's sales performance using Kaggle datasets (Orders and Details). Data was cleaned in Power Query Editor and modeled in Power BI Desktop to build interactive dashboards showing category-wise sales, profit trends, payment mode preferences, and city-level comparisons.
# D-Mart Sales Performance: Profit & Trends Overview

## 📌 Project Overview
This project analyzes D-Mart’s short-term sales performance using Kaggle datasets.  
It focuses on **category-wise contributions, payment mode preferences, monthly profit trends, and city-level comparisons** through an interactive Power BI dashboard.

## 📂 Dataset
- **Orders.csv** – Contains order details (Order ID, Order Date, Customer Name, State, City).
- **Details.csv** – Contains transactional details (Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode).
- Source: Kaggle

## ⚙️ System Approach
- **Data Acquisition:** Imported Kaggle datasets into Power BI Desktop.  
- **Data Preprocessing:** Cleaned using Power Query Editor, handled duplicates, anomalies, and created calculated measures.  
- **Data Modeling:** Linked Orders and Details tables via Order ID, applied DAX measures, defined hierarchies.  
- **Visualization:** Built dashboard showing category-wise sales/profit, payment mode analysis, monthly trends, and city-level comparisons.  
- **Deployment:** Local usage in Power BI Desktop; shared via `.pbix` or exported reports.

## ✅ Findings & Conclusion
- Clothing contributed the highest sales quantity, while Electronics and Furniture showed balanced profit margins.  
- COD was the most preferred payment mode, followed by Credit Card and EMI.  
- Profit trends varied monthly, highlighting peak and low-performing periods.  
- The dashboard effectively transformed raw data into actionable insights, though challenges included cleaning negative profit values.

## 🔮 Future Scope
- Add external data sources (customer demographics, promotions, holidays).  
- Optimize calculations and forecasting models.  
- Expand analysis to multiple cities/regions.  
- Integrate machine learning for predictive analytics.  
- Explore edge computing and AI-powered analytics.  
- Deploy on Power BI Service or cloud platforms for real-time collaboration.

## 📸 Dashboard Preview
![D-Mart Sales Dashboard](Screenshot%202026-03-15%20082250.png)

## 📜 License
This project is licensed under the MIT License.
