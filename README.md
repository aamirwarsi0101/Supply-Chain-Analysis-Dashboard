# 🚚 Supply Chain Performance Dashboard

## 📌 Project Overview

The Supply Chain Performance Dashboard is an interactive Power BI solution designed to monitor sales performance, logistics efficiency, delivery operations, and product category performance. The dashboard enables stakeholders to identify operational bottlenecks, track delivery metrics, and make data-driven business decisions.

---

## 🎯 Business Objective

The objective of this project is to provide a centralized view of key supply chain metrics and answer critical business questions such as:

* How is overall business performance trending?
* Which markets generate the highest revenue?
* What is the current late delivery rate?
* Which regions experience the highest delivery delays?
* Which shipping modes are most frequently used?
* Which product categories contribute the most revenue?

---

## 📊 Key Performance Indicators (KPIs)

* Total Sales: $36.78M
* Total Profit: $3.97M
* Total Orders: 66K
* Total Customers: 21K
* Average Shipping Days: 3.50 Days
* Late Delivery Rate: 54.83%

---

## 📈 Dashboard Features

### Sales Analysis

* Monthly Sales Trend
* Market-wise Sales Performance
* Top Product Categories by Sales

### Logistics Analysis

* Average Shipping Days
* Average Delay Days
* On-Time Delivery Percentage
* Orders at Risk

### Delivery Performance

* Delivery Status Distribution
* Shipping Mode Distribution
* Late Delivery Percentage by Region

### Interactive Filters

* Date Range
* Market
* Shipping Mode
* Category Name

---

## 🛠 Tools & Technologies

* Power BI
* DAX
* Power Query
* Microsoft Excel
* Data Modeling
* Data Visualization

---

## 📋 Business Insights

* Total sales exceeded $36M across all markets.
* The organization served more than 21K unique customers.
* Late deliveries accounted for 54.83% of total orders.
* Despite the high late delivery rate, the average delay was only 0.57 days, indicating that most delays were relatively minor.
* Certain regions experienced significantly higher delivery delays, highlighting opportunities for logistics optimization.
* A small number of product categories contributed a substantial share of total revenue.

---

## 🧮 DAX Measures Used

```DAX
Total Sales = SUM(Supply_Chain_Analysis[Sales])

Total Profit = SUM(Supply_Chain_Analysis[Benefit per order])

Total Orders = DISTINCTCOUNT(Supply_Chain_Analysis[Order Id])

Total Customers = DISTINCTCOUNT(Supply_Chain_Analysis[Customer Id])

Avg Shipping Days =
AVERAGE(Supply_Chain_Analysis[Days for shipping (real)])

Late Delivery % =
DIVIDE(
    SUM(Supply_Chain_Analysis[Late_delivery_risk]),
    COUNTROWS(Supply_Chain_Analysis),
    0
)
```

---

## 📌 Project Outcome

This dashboard provides a comprehensive overview of supply chain performance, helping decision-makers monitor operational efficiency, improve delivery performance, optimize logistics processes, and identify revenue-generating opportunities across markets and product categories.

---

## 👨‍💻 Author

**Aamir Warsi**

Data Analyst

Skills: SQL | Power BI | Excel | Python | Data Visualization | Business Intelligence

LinkedIn: linkedin.com/in/aamir-warsi
GitHub: github.com/aamir414
