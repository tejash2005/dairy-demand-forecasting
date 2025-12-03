🌟 Project Summary – Demand Forecasting & Inventory Optimization for Dairy Supply Chain

🧠 Overview

This project uses forecasting to solve inefficiencies in the dairy supply chain. Using Python, Prophet, XGBoost, and time-series analytics, it predicts 7-day product-wise demand, optimizes inventory, and identifies plant utilization status (Underutilized | Optimal | Overloaded).

The system also provides anomaly detection, ROI estimation, and stock-out alerts, ensuring smarter production planning and minimal wastage.

🚀 Executive Summary

The project improves dairy plant efficiency by forecasting demand and highlighting whether the plant is meeting, exceeding, or falling short of its capacity.

It delivers:

✔ Product-wise demand forecasts
✔ Daily utilization status
✔ Alerts for stock-outs and overload
✔ ROI estimates
✔ Business-ready graphs & CSV outputs

📌 Technology Used: Python, Prophet, Pandas, Matplotlib, Google Colab.

🎯 Objectives
Primary Objective

Forecast product-wise daily demand and calculate plant utilization based on a fixed capacity (2000 liters/kg per day).

Secondary Objectives

Visualize sales trends

Forecast using Prophet

Categorize utilization into:
🔹 Underutilized (<90%)
🔹 Optimal (90–110%)
🔹 Overloaded (>110%)

Provide business-ready CSVs & graphs

Assist decisions for procurement, staffing, & production planning

Measurable Goals

📅 Forecast Horizon: 7 Days

🎯 Accuracy Target: ±15%

🏭 Utilization Categorization: Yes

📊 Output: CSV + Graphs + Alerts

📦 Dataset Overview

The dataset contains daily sales of dairy SKUs:
🧈 Butter | 🥛 Milk | 🍦 Ice Cream | 🥤 Buttermilk | 🍶 Lassi | 🧀 Cheese | 🥣 Curd | Yogurt etc.

Key Features:

Date

Product

Sales Quantity

Total Sales

Category

🔧 Methodology
1️⃣ Data Cleaning & EDA

Missing values handled

Column formatting

Product name standardization

2️⃣ Forecasting (Prophet Model)

Prophet handles:
✔ Trend
✔ Seasonality
✔ Sudden changes
✔ Weekly patterns

Each SKU is forecasted individually → aggregated → total demand.

3️⃣ Plant Utilization Calculation

Utilization % = (Forecasted Demand / Capacity) × 100

4️⃣ Anomaly Detection

Using:

Rolling Median + MAD

Z-Score

Helps detect:
⚠ Sudden spikes
⚠ Drops
⚠ Data errors
⚠ Unexpected demand patterns

🛠 Technologies Used

Python

Prophet (Meta)

Pandas

Matplotlib

Google Colab (Cloud)

Jupyter Notebook

📈 Results & Insights
Key Metrics
Metric	Value
Forecast Duration	7 Days
Forecast Model	Prophet
Plant Capacity	2000 liters/kg
Utilization Status	Underutilized / Optimal / Overloaded
SKUs Forecasted	Multiple dairy products
📊 Major Output Charts

The project includes 10+ business-critical charts, such as:

⭐ Demand vs Plant Capacity

Shows underutilized/overloaded days.

⭐ Estimated Daily ROI

Links forecast accuracy to financial gain.

⭐ Stock-Out Alerts

Forecast vs Stock → highlights shortage risk.

⭐ Milk Supply vs Demand

Helps plan procurement of raw milk.

⭐ Weekly Average Capacity Utilization

Measures week-to-week efficiency.

⭐ Anomaly Detection (MAD + Z-Score)

Flags abnormal demand behavior.

⭐ SKU Switching Cost Chart

Reveals unstable product manufacturing patterns.

🚨 Inventory Optimization & Reorder Alerts

The project generates a 7-day risk table showing which products will run out.

🔥 Key Insight

➡ All 10 products are HIGH RISK and need Immediate Reorder.

Examples:

Lassi → Stock: 338 → Forecast: 2322 → High Risk ❗

Paneer → Stock: 21 → Forecast: 1449 → Extreme Risk ❗

Ghee → Stock: 90 → Forecast: 2249 → High Risk ❗

The table shows:

Current stock

7-day forecast demand

Projected stock-out days

Safety buffer

Reorder quantity

Risk level

💰 ROI Estimation

The model estimates ROI based on efficient production:
✔ Optimal days = highest ROI
✔ Overloaded days = penalty costs
✔ Underutilized days = wasted capacity

⚠️ Risks & Mitigation
Risks

Missing or inconsistent data

Seasonality not captured for rare SKUs

Overfitting

External events (festivals, climate)

Mitigation

✔ Cleaned & preprocessed data
✔ Prophet’s robustness
✔ Manual validation of anomalies
✔ Standardized product names

🟢 Benefits of the System
🎉 Business Benefits

✔ Reduced wastage of perishable products ❄

✔ Improved resource planning

✔ Avoids stock-outs and overproduction

✔ Higher profit margins through optimized ROI

✔ Strong support for procurement & logistics

🎉 Technical Benefits

✔ Scalable forecasting

✔ Easy to automate

✔ Cloud-based (Colab)

✔ Can be extended for 30-day or monthly planning

📝 Conclusion

This project successfully builds an AI-powered demand forecasting and inventory optimization system for dairy supply chains. It:
✔ Predicts product-wise demand
✔ Classifies daily utilization
✔ Identifies anomalies
✔ Provides Stock-Out Alerts
✔ Estimates ROI
✔ Generates business-ready visualizations & CSV output

This system can be expanded into a real-time dashboard and scaled across multiple plants.

🔮 Future Scope

✨ Extend forecasts to 30 days
✨ Add holiday, promotion, and weather data
✨ Integrate into a mobile/desktop dashboard
✨ Full automation with daily data updates
✨ Auto-trigger email/SMS alerts
