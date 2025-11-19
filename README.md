# FOOD-DELIVERY-COST-AND-PROFITABILITY-ANALYSIS
🍔📦 Food Delivery Cost & Profitability Analysis










🧩 Business Problem Statement

Food delivery companies handle thousands of orders daily — each involving delivery charges, packaging costs, restaurant commissions, discounts, and operational fees.
However, not every order is profitable.

High discounts, rising delivery costs, and low-margin orders can lead to hidden losses, making profitability analysis essential.

This project solves the problem by analyzing:

🍽️ How much does each order cost?
📦 Which cost components impact profit the most?
💰 Which orders are profitable vs. loss-making?
📉 How do discounts, delivery distance, and fees affect margins?
📈 What strategies can improve overall profitability?

Through detailed cost breakdown and revenue mapping, the analysis provides strong financial insights for restaurants, delivery platforms, and business stakeholders.

📘 Project Overview

This project performs a complete Food Delivery Cost & Profitability Analysis using Python and exploratory data analytics.
It identifies cost leakages, evaluates order-wise profitability, and provides strategic recommendations for improving financial performance.

The analysis is designed for businesses like:

Food delivery platforms

Cloud kitchens

Restaurant chains

Aggregators

🧰 Tech Stack

Python – Data cleaning & transformation

Pandas – Exploratory data analysis

NumPy – Numerical computations

Matplotlib & Seaborn – Visualizations

Dataset Source: Medium (Food Delivery Profitability Dataset)

🗂️ Project Workflow
1️⃣ Data Collection

Imported Medium dataset

Included order-level details like price, discounts, delivery fees, commissions, etc.

2️⃣ Data Cleaning

Removed missing/duplicate values

Corrected data types

Cleaned inconsistent numeric fields

Standardized column formats

3️⃣ Feature Engineering

Created essential cost components:

Delivery fee

Packaging cost

Discounts

Restaurant commission

Platform charges

Tax & service fee

Final order value

4️⃣ Revenue Calculation

Revenue was computed from:

Order value before discount

Commission percentage

Platform fee

5️⃣ Profit Calculation

For each order:

Profit = Total Revenue – Total Costs


Additionally analyzed:

Profit margin

Loss-making orders

High-cost outliers

6️⃣ Visual Exploration

Built visual insights using Seaborn & Matplotlib:

Cost distribution

Discount impact

Profit vs. loss comparison

Order value vs. profitability

Correlation heatmap

7️⃣ Recommendations

Derived business strategies based on real financial patterns.

🎯 Key Insights

✔ High discounts drastically reduce profitability
✔ Delivery cost is the largest contributor to total expenses
✔ Orders below a certain value often become loss-making
✔ Commission-based revenue is steady but insufficient when discounts are high
✔ Packaging cost increases significantly for single-item orders
✔ A large portion of orders have marginal or negative profit
✔ Optimizing delivery radius improves profitability

📊 Visual Output Highlights

Profit vs Cost Scatterplot

Discount vs Profit Curve

Order Value Distribution

Correlation Heatmap of All Cost Components

Boxplots for outlier detection

Profitability classification chart

📂 Repository Structure
FOOD-DELIVERY-PROFIT-ANALYSIS/
│
├── Food_Delivery_Analysis.ipynb
├── README.md
└── /assets
     └── visualizations.png  (charts from notebook)

🚀 Conclusion

This end-to-end project demonstrates strong analytical skills:

✔ Data cleaning & processing
✔ Cost breakdown & financial modeling
✔ Profitability calculation
✔ Insight extraction
✔ Visualization & storytelling

It showcases your ability to deliver data-driven business insights, suitable for portfolios, interviews, and real-world applications.
