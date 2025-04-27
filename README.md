
# 📊 Credit Card Spends Analysis

## 📝 Problem Statement

This project analyzes credit card transaction data in India to uncover key insights into the spending habits of consumers across various cities, card types, and expense categories.

---

## 📂 About the Dataset

The dataset provides details of credit card transactions made across India. It includes the following fields:

- **City**: The city where the transaction occurred. *(String)*
- **Date**: The date of the transaction. *(Date)*
- **Card Type**: The type of credit card used (e.g., Gold, Silver, Platinum, Signature). *(String)*
- **Expense Type**: The category of expense (e.g., Fuel, Grocery, Entertainment). *(String)*
- **Gender**: The gender of the cardholder. *(String)*
- **Amount**: The transaction amount in Indian Rupees. *(Numeric)*

---

## 🛠️ Tasks to Solve

1. **Top 5 Cities by Spends**  
   - Identify the top 5 cities with the highest total spends.
   - Calculate their percentage contribution to overall credit card spends.

2. **Highest Spend Month per Card Type**  
   - Find the month with the highest spending for each card type.
   - Display the month along with the total amount spent.

3. **Cumulative Spend Milestone (₹10,00,000)**  
   - For each card type, retrieve the transaction details at the point when cumulative spends first reach ₹1,000,000.

4. **City with Lowest Gold Card Spends**  
   - Identify the city with the lowest percentage contribution of spends specifically for the **Gold** card type.

5. **Highest and Lowest Expense Type per City**  
   - For each city, determine:
     - The expense type with the highest total spend.
     - The expense type with the lowest total spend.

6. **Female Spend Contribution by Expense Type**  
   - Calculate the percentage contribution of spends by female cardholders for each expense type.

7. **Highest MoM Growth (January 2014)**  
   - Identify the combination of **card type** and **expense type** that witnessed the highest month-over-month growth in **January 2014**.

8. **Weekend Spend-to-Transaction Ratio**  
   - Find the city with the highest ratio of:
     - Total spends during weekends to
     - Total number of transactions during weekends.

9. **Fastest City to 500 Transactions**  
   - Determine the city that achieved 500 transactions in the least number of days from its first transaction date.

---

## 💡 Key Skills Demonstrated

- Data Aggregation and Grouping
- Cumulative Sums and Milestones
- Percentage Calculations
- Month-over-Month Growth Analysis
- Temporal and City-wise Analysis
- Ratio and Ranking Queries

---

## 📈 Output Expectations

- Clear tabular outputs for each query.
- Insights that can drive business decisions like city prioritization, card type promotions, and targeted marketing strategies.

---
