# Zomato Bengaluru Restaurant Analysis

### Market Intelligence & Business Intelligence Dashboard

An end-to-end **Data Analytics project** analyzing **41,700+ Zomato restaurant listings in Bengaluru** to understand restaurant competition, customer ratings, cuisine trends, online ordering adoption, and value-for-money opportunities.

The project covers the complete analytics workflow — **data cleaning → SQL analysis → Power BI dashboard → business insights**.

---

## 📊 Dashboard Preview

### Market Overview

<img width="1049" height="673" alt="Market Overview" src="https://github.com/user-attachments/assets/5498842e-d0c3-4337-add1-b1d079c7407a" />

### Restaurant Performance

<img width="1051" height="673" alt="Restaurant Performance" src="https://github.com/user-attachments/assets/2b042768-4c09-4984-931c-6d17830b5d51" />

### Value Intelligence

<img width="1048" height="673" alt="Value Intelligence" src="https://github.com/user-attachments/assets/c2bcde52-f454-490b-9802-9ad6da69f54d" />

---

## 🎯 Project Objective

The objective of this project was to transform a large, messy restaurant dataset into an interactive BI solution capable of answering practical business questions around:

* Restaurant market concentration
* Customer satisfaction
* Cuisine popularity
* Restaurant format distribution
* Online ordering adoption
* Price vs. rating relationships
* Value-for-money opportunities

---

## 💼 Business Questions

| #  | Business Question                                                             | Dashboard              |
| -- | ----------------------------------------------------------------------------- | ---------------------- |
| 1  | Where is restaurant competition highest in Bengaluru?                         | Market Overview        |
| 2  | Which dining formats dominate the market?                                     | Market Overview        |
| 3  | How widely has online ordering been adopted?                                  | Market Overview        |
| 4  | Which cuisines dominate the Bengaluru market?                                 | Market Overview        |
| 5  | Which locations have the highest average ratings?                             | Restaurant Performance |
| 6  | Which locations have the lowest customer satisfaction?                        | Restaurant Performance |
| 7  | Do restaurants offering online ordering receive higher ratings or engagement? | Restaurant Performance |
| 8  | Which restaurant types perform best by rating?                                | Restaurant Performance |
| 9  | Does higher spending correspond to better ratings?                            | Value Intelligence     |
| 10 | Where are the high-rated, low-cost restaurants?                               | Value Intelligence     |
| 11 | Which locations provide the best value for money?                             | Value Intelligence     |
| 12 | Which restaurants meet the budget criteria of rating ≥ 4.0 and cost ≤ ₹500?   | Value Intelligence     |

---

## 🔎 Key Insights

### Market Structure

* **BTM Layout** has the highest restaurant concentration, with **4,000+ listings**.
* **Quick Bites** is the most common restaurant format, accounting for approximately **39.9%** of listings.
* **North Indian** is the most represented cuisine category, with **2,200+ restaurants**.

### Restaurant Performance

* **Lavelle Road** records the highest average restaurant rating among the analyzed locations at approximately **4.14**.
* **Bommanahalli** records the lowest average rating among major locations at approximately **3.19**.
* Restaurants offering **online ordering** show higher average customer engagement based on votes.

### Value Intelligence

* Higher-cost restaurant segments tend to have higher average ratings, but **higher spending does not guarantee a better dining experience**.
* Several budget restaurants achieve ratings of **4.0+** while remaining within a cost range of **₹500 or less**.
* The dashboard identifies potential **value-for-money locations and budget restaurant opportunities**.

---

## 📈 Dashboard Structure

### Page 1 — Market Overview

Provides a high-level view of Bengaluru's restaurant market.

**Includes:**

* Total restaurant listings
* Restaurant concentration by location
* Restaurant type distribution
* Online ordering adoption
* Top cuisine categories

### Page 2 — Restaurant Performance

Focuses on restaurant ratings, customer engagement, and location-level performance.

**Includes:**

* Top 10 locations by average rating
* Bottom 10 locations by average rating
* Online ordering vs. rating analysis
* Restaurant type performance
* Top-rated restaurants

### Page 3 — Value Intelligence

Analyzes the relationship between restaurant cost and customer ratings.

**Includes:**

* Cost segment vs. average rating
* Price vs. rating scatter analysis
* Best-value locations
* Budget restaurant opportunities
* High-rating, low-cost restaurants

---

## 🎛️ Interactive Analysis

The Power BI dashboard includes interactive slicers that allow users to filter the analysis by:

* **Online Order**
* **Listed In Type**
* **Book Table**
* **Location**
* **Cuisine**

This allows users to move from a high-level market view to more specific restaurant-level analysis.

---

## 🛠️ Tools & Technologies

| Tool                 | Purpose                                                                 |
| -------------------- | ----------------------------------------------------------------------- |
| **Microsoft Excel**  | Data cleaning, rating extraction, cost formatting, and data preparation |
| **MySQL Workbench**  | SQL-based business analysis and aggregation                             |
| **Power BI Desktop** | Interactive dashboard development and visualization                     |
| **GitHub**           | Project documentation and version control                               |

---

## 🔄 Project Workflow

```text
Raw Zomato Dataset
        ↓
Data Cleaning & Transformation
        ↓
Cleaned Dataset
        ↓
MySQL Data Analysis
        ↓
Business Questions & Insights
        ↓
Power BI Dashboard
        ↓
Interactive Business Intelligence Report
```

---

## 🧹 Data Preparation

The original dataset contained inconsistent and messy values that required preprocessing before analysis.

Key cleaning steps included:

* Extracting usable numerical ratings from rating fields
* Standardizing restaurant cost values
* Handling missing and inconsistent values
* Removing/identifying duplicate records
* Preparing categorical fields for analysis
* Creating a clean dataset for SQL and Power BI

The original dataset was preserved separately to maintain data lineage.

---

## 🗄️ SQL Analysis

The project includes **10 SQL business queries** covering areas such as:

* Restaurant concentration by location
* Average ratings by location
* Minimum restaurant-count thresholds
* Restaurant type performance
* Cuisine distribution
* Online ordering analysis
* High-rated restaurants
* Budget restaurant identification

SQL was used to validate patterns and generate analytical outputs before building the Power BI dashboard.

---

## 📁 Project Structure

```text
Zomato_Restaurant_Analysis/
│
├── data/
│   ├── zomato_original.csv
│   ├── zomato_working.xlsx
│   └── zomato_clean.csv
│
├── sql/
│   └── zomato_queries.sql
│
├── powerbi/
│   └── zomato_dashboard.pbix
│
└── README.md
```

---

## 📦 Project Files

| File                    | Description                             |
| ----------------------- | --------------------------------------- |
| `zomato_original.csv`   | Original raw dataset                    |
| `zomato_working.xlsx`   | Working file used during data cleaning  |
| `zomato_clean.csv`      | Final cleaned dataset used for analysis |
| `zomato_queries.sql`    | SQL business analysis queries           |
| `zomato_dashboard.pbix` | Three-page Power BI dashboard           |

---

## 📊 Dataset

**Source:** [Kaggle — Zomato Bangalore Restaurants](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)

| Attribute    | Details                     |
| ------------ | --------------------------- |
| Location     | Bengaluru, India            |
| Records      | 41,700+ restaurant listings |
| Columns      | 17                          |
| Dataset Type | Restaurant listing data     |
| Source       | Kaggle                      |

---

## 💡 Business Value

This project demonstrates how raw restaurant data can be transformed into actionable business intelligence.

The analysis can help stakeholders understand:

* **Market concentration** → where competition is strongest
* **Customer satisfaction** → which locations and formats perform better
* **Consumer preferences** → which cuisines and restaurant types dominate
* **Digital adoption** → prevalence of online ordering
* **Pricing strategy** → relationship between cost and ratings
* **Market opportunities** → locations and restaurants offering strong value

---

## 🚀 Skills Demonstrated

**Data Analytics**

* Data Cleaning
* Exploratory Data Analysis
* Business Question Formulation
* KPI Analysis
* Insight Generation

**SQL**

* Aggregations
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* Filtering
* Ranking
* Conditional analysis

**Power BI**

* Interactive dashboards
* KPI cards
* Slicers
* Bar charts
* Scatter plots
* Tables
* Business storytelling

**Excel**

* Data transformation
* Data cleaning
* Formatting
* Data validation

---

## 👤 Connect

**Sahil Bharude**

* [LinkedIn](https://www.linkedin.com/in/sahilbharude/)
* [GitHub](https://github.com/BharudeSahil)
* [Email](bharudesahil@gmail.com)

---

## ⭐ If you found this project useful

Feel free to explore the SQL queries, cleaned dataset, and Power BI dashboard to see how the analysis was developed from raw data to business insights.
