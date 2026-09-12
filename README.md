# Supply-Chain-Analysis-
# E-Commerce Supply Chain Performance & Logistics Optimization

## 📌 Project Overview

This project analyzes supply chain and logistics performance using the **DataCo Smart Supply Chain** dataset containing **180K+ order-level records and 55+ columns** across provisioning, production, sales, and commercial distribution.
<br>
The analysis focuses on identifying **delivery delays, operational bottlenecks, profitability patterns, and high-risk regions, products, customer segments, and shipping modes**.
<br>
The objective is to move beyond descriptive reporting and identify **business problems, their potential root causes, and actionable opportunities for logistics optimization**.
<br>

## 🎯 Business Problem

E-commerce businesses need to balance fast and reliable delivery with operational efficiency and profitability.
This analysis aims to answer questions such as:
* How effectively is the supply chain performing?
* What proportion of orders are delayed?
* Which regions and markets experience the highest delivery risk?
* Which shipping modes contribute to delays?
* Are certain customer segments more affected by delivery issues?
* How do delays relate to profitability?
* Which operational areas should management prioritize?
* What opportunities exist to improve delivery performance and profitability?

### Business Flow

**Orders → Shipping → Delivery → Delays → Profitability → Root Causes → Recommendations**

---

## 📊 Dataset

**Dataset:** DataCo Smart Supply Chain

The dataset contains information related to:

* Orders and sales
* Products and categories
* Customers and segments
* Shipping modes
* Delivery dates
* Order and shipping status
* Geographic regions and markets
* Product profitability
* Operational and transactional information

**Dataset Size:** 180K+ records
**Features:** 55+ columns

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                             |
| -------------- | --------------------------------------------------- |
| **Python**     | Data cleaning, transformation, exploratory analysis |
| **Pandas**     | Data manipulation and feature engineering           |
| **NumPy**      | Numerical analysis                                  |
| **SQL**        | Data extraction, aggregation, and business analysis |
| **Excel**      | Data validation and scenario analysis               |
| **Power BI**   | Interactive dashboard and business reporting        |
| **PowerPoint** | Consulting-style recommendations and presentation   |

---

## 🔄 Project Workflow

### 1. Data Understanding

* Examined dataset structure and dimensions
* Reviewed data types and categorical variables
* Identified relevant business and operational fields
* Checked data quality and consistency

### 2. Data Cleaning

* Removed unnecessary columns
* Handled irrelevant records
* Filtered out cancelled orders where appropriate
* Checked for missing and inconsistent values
* Prepared the dataset for analysis

### 3. Feature Engineering

Created analytical fields to support supply chain performance analysis, including:

* **Processing Time**
* **Delay**
* **Is_Delayed**
* **Profitability Flag**

These features were used to connect operational performance with business outcomes.

### 4. Exploratory Data Analysis

The analysis investigates:

* Order and sales performance
* Delivery performance
* Delay patterns
* Processing time
* Regional performance
* Shipping mode performance
* Customer segment performance
* Product/category performance
* Profitability
* Time-based trends

### 5. SQL Analysis

SQL was used to perform business-oriented analysis such as:

* Aggregations
* Grouping and filtering
* Regional comparisons
* Shipping-mode analysis
* Customer-segment analysis
* Delay and profitability analysis
* Identification of operational problem areas

### 6. Power BI Dashboard

The final analysis is presented through an interactive Power BI dashboard designed to help decision-makers quickly identify:

* Overall supply chain KPIs
* Delivery performance
* Delay trends
* Regional risks
* Shipping-mode performance
* Segment-level performance
* Profitability patterns
* Areas requiring operational attention

---

## 📈 Key KPIs

The dashboard focuses on metrics such as:

* **Total Orders**
* **Total Sales**
* **Total Profit**
* **Average Order Value**
* **Delayed Orders**
* **Delay Rate**
* **Average Processing Time**
* **Average Delivery Time**
* **Profitability Rate**

These KPIs provide a high-level view of both **operational efficiency and financial performance**.

---

## 🔍 Key Business Analysis Areas

### 🌍 Regional Performance

Regions and markets were compared to identify geographic areas with:

* Higher delay rates
* Longer processing times
* Lower profitability
* Greater operational risk

This helps identify locations that may require logistics or fulfillment improvements.

### 🚚 Shipping Mode Analysis

Shipping modes were analyzed to understand differences in:

* Delivery performance
* Delay rates
* Processing time
* Profitability

The goal is to identify whether certain shipping methods consistently create higher operational risk.

### 👥 Customer Segment Analysis

Customer segments were evaluated based on:

* Order volume
* Sales
* Profitability
* Delivery performance
* Delay patterns

This helps determine whether operational issues are concentrated within particular customer groups.

### 📦 Product & Category Analysis

Products and categories were examined to identify:

* High-volume products
* High-profit products
* Low-profit products
* Products associated with delivery issues
* Categories requiring operational attention

### ⏱️ Delay & Processing Analysis

Delivery delays were analyzed alongside processing time to investigate potential operational bottlenecks.

The analysis distinguishes between:

**Operational processing → Shipping → Delivery → Delay**

This helps move the analysis from simply identifying *what is delayed* toward understanding *where the delay may be occurring*.

---

## 💡 Business Insights

The analysis is structured around identifying:

1. **Where delays are concentrated**
2. **Which operational factors are associated with delays**
3. **Which regions and shipping modes carry higher risk**
4. **Whether delayed orders are associated with weaker profitability**
5. **Which products or segments require attention**
6. **Where logistics improvements could have the greatest business impact**

The final recommendations are designed from a **business and consulting perspective**, rather than focusing only on technical findings.

---

## 📊 Dashboard

The Power BI report provides an interactive view of supply chain performance.

Users can analyze performance across dimensions such as:

* Region
* Market
* Shipping Mode
* Customer Segment
* Product Category
* Time
* Delivery Status

Interactive filters and visuals allow users to move from **overall performance → problem identification → root-cause analysis**.

---

## 🎯 Recommendations Framework

The final recommendations focus on areas such as:

### 1. Logistics Optimization

Review high-delay shipping modes and evaluate whether alternative logistics strategies can improve delivery reliability.

### 2. Regional Prioritization

Prioritize regions with consistently high delay rates or weaker profitability for operational review.

### 3. Process Improvement

Investigate stages with longer processing times to identify fulfillment bottlenecks.

### 4. Product-Level Monitoring

Monitor products or categories where delivery issues and weak profitability occur together.

### 5. Performance Monitoring

Establish recurring KPIs for delay rate, processing time, delivery performance, and profitability to track improvement over time.

---

## 📁 Project Structure

```text
Supply-Chain-Analysis/
│
├── data/
│   └── DataCo_Smart_Supply_Chain.csv
│
├── notebooks/
│   └── supply_chain_analysis.ipynb
│
├── sql/
│   └── supply_chain_analysis.sql
│
├── powerbi/
│   └── supply_chain_dashboard.pbi
```
