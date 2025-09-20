# 📊 Data Unity Challenge – Reto #7: Top Customers & Average Spending

## 🏪 Business Context

This challenge focuses on identifying the most valuable customers in a supermarket dataset. Understanding who spends the most can help businesses design loyalty programs, targeted discounts, and personalized promotions.

This analysis is part of the **Data Unity Challenge**, a bilingual initiative to empower data analysts through creative, community-driven projects.

---

## 🎯 Objective

- Calculate total spending per customer.
- Identify the top 5 customers by total contribution to sales.
- Calculate the average spending across all customers.
- Visualize the results with:
  - A bar chart for the top 5 customers.
  - A histogram (with density curve) for spending distribution.
- Share key insights and strategic recommendations.

---

## 🗂️ Dataset Overview

- **Source**: Supermarket transactions (1,500 rows)
- **Key columns**:
  - `CustomerID`: Unique identifier for each customer.
  - `TotalSales`: Total amount spent per transaction.

---

## 🧮 Methodology

1. Group transactions by `CustomerID` and sum `TotalSales`.
2. Sort customers by total spending to identify the top 5.
3. Calculate the average spending across all customers.
4. Visualize:
   - Top 5 customers using a bar chart.
   - Spending distribution using a histogram with KDE.

---

## 📊 Visualizations

### 🏆 Top 5 Customers by Total Spending

![Top 5 Customers Bar Chart](top_5_customers.png)

> Customers C0070 and C0030 lead the pack, followed by C0168, C0198, and C0101.

---

### 📉 Distribution of Total Spending per Customer

![Spending Distribution Histogram](spending_distribution.png)

> The distribution is right-skewed, with most customers spending under $200. A few outliers exceed $400.

---

## 📈 Key Findings

- **Top 5 Customers**:
  - C0070
  - C0030
  - C0168
  - C0198
  - C0101

- **Average Spending per Customer**: **$159.79**

- The top 5 customers represent a significant portion of total sales, indicating high-value behavior.

- The majority of customers spend less than $200, suggesting opportunities to increase engagement and spending.

---

## 💡 Recommendations

Depending on the supermarket’s strategy, several loyalty initiatives could be considered:

- 🎁 **Reward Programs**: Offer exclusive perks to top spenders.
- 💸 **Tiered Discounts**: Create spending brackets with increasing benefits.
- 📩 **Targeted Promotions**: Use personalized offers to boost retention and upsell.

These strategies can help retain high-value customers while motivating others to increase their engagement.

---

## 🌐 About Data Unity Challenge

The **Data Unity Challenge** is a bilingual, community-driven initiative that blends data analysis with creativity, humor, and collaboration. This project is part of a series designed to empower analysts through relatable content, visual storytelling, and hands-on challenges.

Follow the journey on LinkedIn and join the movement to learn, laugh, and grow together.

---

