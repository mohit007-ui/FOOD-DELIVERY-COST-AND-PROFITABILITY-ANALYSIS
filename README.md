🍔📦 Food Delivery Cost & Profitability Analysis










🧩 Business Problem Statement

Food delivery platforms incur several direct and indirect costs such as delivery fees, discounts, payment processing charges, and refunds. At the same time, their primary source of revenue is the commission fee charged to restaurants.

This project analyzes:

Whether each order is profitable or loss-making

How discounts impact profitability

How much revenue commissions generate

Whether the delivery platform’s current pricing model is sustainable

What commission/discount percentages lead to profit

The goal is to identify the break-even point and recommend strategies to turn unprofitable orders into profitable ones.

📘 Project Overview

This project performs a complete cost and profitability analysis on food delivery orders using Python.
It includes:

✔ Data cleaning
✔ Discount extraction and calculation
✔ Cost & revenue computation
✔ Order-level profit calculation
✔ Visual analysis
✔ Simulation of profitability using recommended discount & commission percentages

🧰 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Dataset Source: Medium (food_orders_new_delhi.csv)

🗂️ Project Workflow
1️⃣ Data Loading & Initial Exploration

Loaded a dataset of 1000 food delivery orders

No missing values except discount column in some cases

Verified data types and structure

2️⃣ Data Cleaning

Converted

Order Date and Time → datetime

Delivery Date and Time → datetime

Extracted numeric discount values from strings like:

"10%"

"15% New User"

"50 off Promo"

"None"

3️⃣ Discount Handling Logic

Created two new fields:

🔹 Discount Percentage

Percentage-based discount extracted from “%”

Fixed discounts extracted from “off”

🔹 Discount Amount

Calculated as:

If percentage discount → (Order Value × %)
If fixed discount → fixed amount
If none → 0

4️⃣ Cost Computation

Total platform cost per order:

Total Costs = Delivery Fee + Payment Processing Fee + Discount Amount

5️⃣ Revenue & Profit Calculation

Platform revenue (per order):

Revenue = Commission Fee


Profit:

Profit = Revenue – Total Costs

6️⃣ Overall Financial Summary

After analyzing 1000 orders:

Metric	Value
Total Orders	1000
Total Revenue	126,990 INR
Total Costs	232,709.85 INR
Total Profit	–105,719.85 INR (Loss)

👉 The platform is overall loss-making because discounts + delivery + payment fees exceed commission revenue.

📊 Visual Analysis
✔ Profit Distribution

Histogram showing majority of orders generating negative profit.

✔ Cost Breakdown

Pie chart of:

Delivery Fee

Payment Processing Fee

Discount Amount
Most cost comes from discounts.

✔ Revenue vs Costs vs Profit

Bar chart showing:

Costs > Revenue → Net loss

🎯 Strategy: Finding the Profit Sweet Spot

Analyzed only profitable orders to find sustainable values:

New Average Commission % (Profitable Orders): ~30.5%

New Average Discount % (Profitable Orders): ~5.8%

This indicates:

✔ Higher commissions increase profitability
✔ Lower discounts significantly reduce losses

🧪 Profitability Simulation

Simulated profitability using:

Commission = 30%

Discount = 6%

Recomputed:

Simulated Commission Fee

Simulated Discount Amount

Simulated Profit

📈 Density plots show that profitability shifts toward positive when recommended values are used.

📂 Repository Structure
FOOD_DELIVERY_COST_PROFIT_ANALYSIS/
│
├── Food_Delivery_Cost_Profitability.ipynb
├── food_orders_new_delhi.csv
└── README.md

🚀 Conclusion

This project delivers a clean, actionable profitability analysis:

✔ Extracted & standardized discount values
✔ Computed order-level cost, revenue, and profit
✔ Identified that current model is loss-making
✔ Found optimal discount & commission values
✔ Simulated future profitability improvements

The analysis proves that reducing discounts and increasing commission rates can turn an unprofitable delivery model into a profitable one.
