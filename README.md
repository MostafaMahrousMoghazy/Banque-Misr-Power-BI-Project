# Banque Misr Banking Analytics Dashboard | Power BI

Which branches, cities, and customers are actually driving the bank's performance?

This is what this project answers.

## 📊 Project Overview

An interactive **Banking Analytics Dashboard built with Microsoft Power BI**, designed to provide a consolidated view of banking performance across:

- Customers
- Accounts
- Loans
- Transactions
- Branches

The dashboard transforms banking data into interactive KPIs and visualizations that help explore customer segments, account balances, loan performance, transaction behavior, and branch-level activity.

The report is organized into six main analytical pages:

1. Overview
2. Customers
3. Accounts
4. Loans
5. Transactions
6. Branches

---

## 🧩 Data Model

The data model connects the main entities used in the analysis.

![Data Model](Project/Data%20Modeling/Data%20Modeling.PNG)

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Monitor key banking KPIs
- Analyze the customer base by segment, city, and gender
- Understand account distribution and balances
- Monitor loan performance and default activity
- Analyze transaction amounts, channels, and types
- Compare banking activity across branches and cities
- Build an interactive dashboard with consistent filtering
- Present banking data in a clear, business-oriented format

---

# 🏦 Dashboard Structure

## 1. Executive Overview

The Overview page provides a high-level snapshot of the banking business.

**KPIs**
- Total Balance
- Loans Outstanding
- Total Customers
- Default Rate

**Visualizations**
- Customer Segment Mix
- Monthly Transactions Trend
- Deposit Balance by City

**Filters**
- Segment
- City
- Date

The overview also compares deposit balances across cities, including:

- Mansoura – Delta
- Assiut – Upper Egypt
- Cairo – Greater Cairo
- Giza – Greater Cairo
- Alexandria – Delta
- Tanta – Delta
- 
![Overview](Project/Images/page%2002.jpg)

---

## 2. 👥 Customers

The Customers page focuses on customer demographics and financial characteristics.

**KPIs**
- Total Customers
- Average Monthly Income
- VIP Customers
- Average Tenure

**Visualizations**
- Income vs Balance
- Customers by City
- Customers by Gender

**Customer dimensions**

Customers can be explored by:

- Segment
- City
- Date
- Gender

**Customer segments**
- Retail
- Mass
- VIP

![Overview](Project/Images/page%2003.jpg)

---

## 3. 💳 Accounts

The Accounts page provides an overview of customer accounts and balances.

**KPIs**
- Total Accounts
- Total Balance
- Average Interest Rate
- Accounts per Customer

**Visualizations**
- Account Type Split
- Average Interest Rate by Account Type
- Account Details

**Account types**
- Savings
- Current
- Fixed

**Account Details table columns**
- Account ID
- Account Type
- Balance
- Branch Name

![Overview](Project/Images/page%2004.jpg)

---

## 4. 💰 Loans

The Loans page analyzes the bank's loan portfolio and loan status.

**KPIs**
- Total Loans Book
- Default Rate
- Average Interest Rate
- Average Installments

**Visualizations**
- Loan Type by Status
- Loan Status Mix
- Loans Over Time

**Loan types**
- Car
- Personal
- Mortgage

**Loan statuses**
- Active
- Closed
- Defaulted

![Overview](Project/Images/page%2005.jpg)

---

## 5. 💸 Transactions

The Transactions page analyzes transaction activity and channels.

**KPIs**
- Total Transaction Amount
- Transaction Count
- Average Transaction Size
- Digital Share

**Visualizations**
- Transactions by Channel
- Transactions by Type
- Top Customers by Transactions

**Transaction channels**
- ATM
- Branch
- Online

**Transaction types**
- Deposit
- Withdrawal
- Payment
- Transfer

![Overview](Project/Images/page%2006.jpg)

---

## 6. 🏢 Branches

The Branches page provides a branch-level view of banking activity.

**KPIs**
- Total Branches
- Total Employees
- Balance per Branch
- Loans per Branch

**Visualizations**
- Total Balance by City
- Top Branch by Volume

The dashboard compares branch activity across cities and displays branch-level volumes.

![Overview](Project/Images/page%2007.jpg)

---

# 🔎 Interactive Filters

The report uses common filters across the analytical pages:

- Segment
- City
- Date

These filters let users interactively explore the banking data across different customer groups, locations, and time periods.

## ❓ Key Questions This Dashboard Answers

### Overview
**- Q: What is the bank's current deposit base versus its lending exposure?**

Total balance across all customer accounts stands at 299.42M EGP against 156.86M EGP in loans outstanding — deposits currently outweigh loan exposure by close to 2x.

**- Q: How healthy is the loan portfolio at a glance?**

The default rate sits at 8.33% across the portfolio, visible on the executive summary without drilling into the Loans page.

**- Q: How is the customer base split by segment?**

Retail customers make up 60% (600) of the base, Mass 30% (300), and VIP just 10% (100).

**- Q: Which cities hold the most deposits?**

Mansoura leads, followed by Assiut, Cairo, Giza, Alexandria, with Tanta lowest.

**- Q: Is transaction activity seasonal?**

Yes — monthly transaction volume peaks in November (7.7M EGP) and June (7.2M EGP), with troughs around February, September, and October (5.6–5.7M EGP).

### Customers
**- Q: What is the typical customer profile?**

Average monthly income is 38.63K EGP, and the average customer has stayed with the bank 6.65 years.

**- Q: Does income relate to account balance?**

Not strongly — most customers cluster at low income and low balance regardless of income level, with only a handful of high-income/high-balance outliers.

**- Q: Is the customer base concentrated in specific cities?**

Fairly evenly spread — Mansoura (177) and Alexandria (176) lead, Giza is lowest at 151.

**- Q: Is there a gender imbalance in the customer base?**

No — the split is almost even at 50.3% male to 49.7% female.

### Accounts
**- Q: How diversified is the account base by type?**

Nearly evenly split — Savings (33.71%), Fixed (33.23%), and Current (33.07%) each represent roughly a third of accounts.

**- Q: Which account type costs the bank the most in interest?**

Fixed accounts carry the highest average rate at 7.02%, just above Savings (6.94%) and Current (6.91%).

**- Q: How much cross-sell is happening?**

Accounts per customer sits at 1.24 — most customers hold only a single account.

### Loans
**- Q: Which loan type carries the most default risk?**

Mortgage loans have the highest defaulted amount (4M EGP) despite a smaller active book (40M EGP) than Car (67M EGP) or Personal (50M EGP) — proportionally, mortgages default more.

**- Q: What share of the loan book is currently healthy?**

65% of loans (391) are Active, 27% (159) Closed, and 8% (50) Defaulted.

**- Q: Is lending volume trending in a clear direction?**

No steady trend — loan issuance is spiky, with recurring volume peaks across 2019–2024 rather than one clear upward or downward trajectory.

### Transactions
**- Q: How digital is the customer base?**

65.81% of transaction value flows through digital channels (ATM and Online combined). By individual channel, Online and ATM are tied at 34% each, with Branch at 32%.

**- Q: Which transaction type dominates?**

Deposits lead slightly (19.4M EGP), followed by Withdrawals (19.1M EGP), Payments (18.6M EGP), and Transfers (17.2M EGP).

**- Q: Who are the highest-value customers by transaction activity?**

Customer 991 leads with 602,531 EGP across 4 deposits, followed by customer 946 (511,323 EGP) and customer 917 (501,301 EGP).

### Branches
**- Q: How many branches and staff does the bank operate?**

20 branches with 506 employees combined — about 25 employees per branch.

**- Q: Which branch generates the most volume?**

Branch_9 leads at 6.3M EGP, while Branch_16 trails at 2.2M EGP — roughly a 3x gap.

**- Q: Which cities carry the most balance at the branch level?**

Mansoura again leads at 77.72M EGP, nearly 1.5x the next-highest city (Assiut, 57.76M EGP), with Tanta lowest at 27.11M EGP.
