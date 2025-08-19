Got it 👍 thanks for clarifying — since your project has **3 main reports (Sales Trend, Customers, Orders)** we’ll restructure the repo README and folder layout to match your work.

Here’s how I’d design your repo in a **professional & portfolio-ready style**:

---

# 🎄 Christmas Sales Insights – Holiday Consumer Behavior Dashboard

An end-to-end **Power BI solution** developed for the **Holiday Sales Challenge**, where I secured **2nd Runner-Up** 🏆.

The project explores **Christmas shopping behavior** with 3 focused reports: **Sales Trends, Customer Insights, and Order Analysis**.

---

## 📊 Dashboard Snapshots

### 1️⃣ Sales Trends

*(Christmas vs. Non-Christmas Sales, Growth Patterns)* 
<img width="1395" height="785" alt="01" src="https://github.com/user-attachments/assets/09ec6e31-85fb-42ad-a247-f8bf7cb98fc1" />


### 2️⃣ Customer Insights

*(Age, Gender, Regional Analysis)* 
<img width="1392" height="782" alt="02" src="https://github.com/user-attachments/assets/f6f15199-e254-47dc-9468-1e6f8fe3b462" />


### 3️⃣ Order Analysis

*(Promotions, Gift Wrapping, Returns, Delivery & Satisfaction)* 
<img width="1391" height="785" alt="03" src="https://github.com/user-attachments/assets/f995b056-877b-4a52-b05b-4ab946c334ca" />


---

## 🧾 Reports Included

| Report No. | Report Title          | Key Focus Areas                                                       |
| ---------- | --------------------- | --------------------------------------------------------------------- |
| 1          | **Sales Trends**      | Seasonal trends, Christmas vs. Non-Christmas sales, Regional patterns |
| 2          | **Customer Insights** | Age, Gender, Location, Purchase behavior                              |
| 3          | **Order Analysis**    | Promotions, Gift wrapping, Express shipping, Returns, Satisfaction    |

---

## 🧩 Key Visuals & Features

### ✅ Sales Trends

* Line Chart: Christmas vs. Non-Christmas Sales
* Map: Sales Distribution by Region
* KPI Cards: MoM Growth, Total Christmas Sales %

### ✅ Customer Insights

* Bar Charts: Sales by Age & Gender
* Heatmap: Regional Purchase Intensity
* Donut: Customer Segmentation

### ✅ Order Analysis

* Bar Chart: Effectiveness of Promotions
* Donut: Gift Wrapping Adoption
* Combo Chart: Delivery Time vs. Satisfaction
* Matrix: Returns by Category & Period

---

## 📐 Example DAX Measures

```DAX
Christmas Sales = 
CALCULATE(
    SUM(Sales[Amount]),
    FILTER(Sales, MONTH(Sales[Date]) = 12)
)

MoM Growth % = 
DIVIDE([This Month Sales] - [Last Month Sales], [Last Month Sales])
```

```DAX
Satisfaction Score = 
AVERAGE(Orders[Satisfaction])
```

```DAX
Gift Wrapping % = 
DIVIDE(
    COUNTROWS(FILTER(Orders, Orders[GiftWrapping] = "Yes")),
    COUNTROWS(Orders),
    0
)
```

---

## 🔍 Insights Uncovered

* 🎄 **Christmas boosts sales by 40–60%** compared to non-holiday months.
* 👩 **Females aged 25–40** are the most active holiday shoppers.
* 🎁 Promotions like **Buy-One-Get-One (BOGO)** drive the highest uplift in sales.
* 📦 **Express shipping & gift wrapping** adoption peaks during Christmas.
* 😊 Satisfaction declines when **delivery delays** occur, leading to higher return rates.

---

## 🚀 Tech Stack

* **Power BI** – Reports & data storytelling
* **DAX** – Custom KPIs & measures
* **Excel** – Data preprocessing
* **Figma/Canva** – Dashboard design layout
* **ChatGPT** – Documentation & DAX support

---

## 🏆 Achievement

🥈 Secured **2nd Runner-Up** position in the Holiday Sales Challenge (global participation).

---

## 📬 Connect with Me

🔗 [LinkedIn – Qasim Tasawar](https://www.linkedin.com/in/qasimtasawar/)
💬 Open to collaborations, feedback, or discussions on Power BI & data storytelling.

