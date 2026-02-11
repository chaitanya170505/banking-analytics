# 🏦 Banking Risk Analytics – End-to-End Data Analytics Project

## 📌 Project Overview

This project focuses on analyzing **customer financial behavior** to drive **personalized banking product recommendations**.
By integrating **Python for Exploratory Data Analysis (EDA)** and **Power BI for interactive visualization**, the project transforms **3,000+ customer records** into actionable business intelligence.

The core objective is to move beyond traditional analysis and capture the **complexity of income patterns, account activity, and product usage** to identify **high-value customer segments**.

---

## 🗂️ Repository Structure

```text
├── data/
│   └── banking_data.csv             # 3,000 customer records
├── scripts/
│   └── Analysis.ipynb               # Python cleaning & EDA
├── powerbi/
│   └── Banking_Analytics.pbix       # Power BI dashboard
├── documentation/
│   └── Project_Details.docx         # Business requirement document
└── README.md
```

---

## 📊 Data Architecture

The dataset consists of **25 attributes**, categorized into four analytical pillars:

### 1️⃣ Demographics

* Age
* Gender
* Nationality
* Occupation

### 2️⃣ Relationship

* Joined Bank
* Banking Contact
* IA (Investment Advisor)
* BR (Branch)

### 3️⃣ Status

* Loyalty Classification
* Fee Structure
* Risk Weighting

### 4️⃣ Financials

* Bank Deposits
* Bank Loans
* Checking Accounts
* Saving Accounts
* Foreign Currency Accounts
* Business Lending
* Superannuation Savings

---

## 🛠️ Technical Implementation

### Phase 1: Data Preprocessing & EDA (Python)

* **Data Cleaning**

  * Handled missing values
  * Standardized numerical formats
* **Exploratory Data Analysis**

  * Correlation analysis between income, risk, and borrowing
  * Distribution analysis across demographics
* **Feature Engineering**

  * Created age groups
  * Derived income bands for customer segmentation

**Libraries Used**

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

### Phase 2: Dashboard Design (Power BI)

The Power BI dashboard contains **three interactive views** with **button-based page navigation**:

#### 🏠 Home Dashboard

* KPIs:

  * Total Clients
  * Total Deposits
  * Total Loans
  * Average Income
* High-level overview of customers and advisor performance

#### 💳 Loan Analysis

* Loan distribution by:

  * Income band
  * Gender
* Risk weighting vs. borrowing capacity

#### 💰 Deposit Analysis

* Deposit breakdown by account type:

  * Checking
  * Saving
  * Foreign Currency
* Contribution analysis by customer segment

---

## 💡 Key Business Insights

### 🔹 The “Full-Wallet” Effect

Customers with the **largest savings and deposits** are also the **largest borrowers**, suggesting wealth is actively leveraged for business and investment purposes.

### 🔹 Risk vs. Activity

A higher **Risk Weighting** does **not** indicate higher default risk in this dataset.
Instead, it reflects **high-income customers managing complex financial portfolios**.

### 🔹 Ageless Performance

High earnings and significant loan activity are observed **across all age groups**, from young professionals to retirees.

---

## 🛠 Tools & Technologies

* **Programming:** Python
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Business Intelligence:** Power BI (DAX)
* **Version Control:** Git

