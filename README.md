<!-- Banner placeholder, replace this image with your own custom banner once ready -->
<p align="center">
  <img src="https://via.placeholder.com/1200x300/0d1117/58a6ff?text=Mai+Truong" alt="Banner placeholder" width="100%">
</p>

# 👋 Hi, I'm Mai Truong

**Data Analyst** based in Finland 🇫🇮. SQL, Python, and Power BI, with a lot of curiosity about why the numbers look the way they do.

---

## ✨ About Me

I clean, query, analyze, and visualize data, mostly because I like knowing why a number looks the way it does, not just what it says.

Before analytics, I spent 3+ years in a metrics-driven SaaS environment working directly with stakeholders, turning vague asks into numbers people could actually use. I got into data through a background in Education and EdTech, and I'm now pivoting into analytics full-time.

---

## 🛠️ Tech & Tools

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Qlik%20Sense-009845?style=for-the-badge&logo=qlik&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
</p>

---

## 🚀 My Projects

### 🗄️ SQL

**[Retail Sales & Inventory Performance Analysis](https://github.com/maitruong-data/Retail-Sales-Inventory-Performance-Analysis-SQL-BigQuery)**<br>
*AdventureWorks dataset · 230K+ records · 8 BigQuery queries*<br>
**Built for:** inventory and merchandising managers deciding which categories to stock up on, and operations teams following up on the $3.87M in stalled orders.
- **Question:** Which products and territories drive growth, and where is the business losing money to weak retention, poor stock alignment, or stalled orders?
- **Approach:** Wrote 8 SQL queries in BigQuery covering YoY growth, territory ranking, discount cost, cohort retention, and stock-to-sales ratios.
- **Recommendation:** Prioritize core bike categories and fast-growing subcategories in inventory planning; investigate the 224 pending orders worth ~$3.87M.

**[E-commerce Web Performance & Customer Purchasing Behaviour Analysis](https://github.com/maitruong-data/Ecommerce-Web-Performance-Customer-Purchasing-Behaviour-Analysis-SQL-BigQuery)**<br>
*Google Analytics Sample Store · 500K+ session logs · 8 BigQuery queries*<br>
**Built for:** marketing managers deciding channel budget and how to promote cross-sell bundles, and the product/UX team improving site search, filters, and navigation to cut funnel drop-off.
- **Question:** Where in the funnel do users drop off, which channels actually convert, and what products could be cross-sold?
- **Approach:** Built a cohort funnel (view → cart → purchase) and traffic-source revenue breakdown, then compared browsing behavior between buyers and non-buyers.
- **Recommendation:** Shift budget toward the highest-converting channels, fix the product-page experience at the biggest funnel drop-off, and use "frequently bought together" bundles to lift order value.

────────────────────

### 🐍 Python

**[Transaction & Payment Analysis for E-Wallet Company](https://github.com/maitruong-data/Transaction-Payment-Analysis-for-E-Wallet-Company-Python)**<br>
*1.3M+ transactions across 3 datasets · Python/Pandas*<br>
**Built for:** risk and operations managers deciding which teams and refund sources to monitor, and product managers weighing the concentration risk in top-performing products.
- **Question:** Which products and teams are driving or dragging performance, and where are refunds and data-quality issues concentrated?
- **Approach:** Cleaned and merged transaction, payment, and product data, then built rule-based logic to classify every transaction into 6 business types.
- **Recommendation:** Flag the concentrated product-volume risk, investigate the refund source responsible for ~60% of refund volume, and prioritize a performance review for the weakest team since Q2 2023.

────────────────────

### 🤖 Machine Learning

**[E-commerce Churn Prediction (Supervised & Unsupervised Learning)](https://github.com/maitruong-data/ECommerce-Churn-Prediction-Supervised-Unsupervised-Learning)**<br>
*5,630 users · scikit-learn · supervised + unsupervised learning*<br>
**Built for:** retention/CRM managers deciding who to target with retention offers, and customer support managers prioritizing response to at-risk complaints.
- **Question:** Which customers are likely to churn, and can churned users be grouped into segments for more targeted retention?
- **Approach:** Trained and tuned a Random Forest classifier (GridSearchCV) for churn prediction, then applied PCA and K-Means to explore segmentation among churned users.
- **Recommendation:** Prioritize retention efforts on new customers and fast complaint response; treat the inconclusive clustering as a data gap to close, not a finished segmentation.

────────────────────

### 📊 Power BI

**[Fashion Marketing & Sales Analysis](https://github.com/maitruong-data/Fashion-Marketing-and-Sales-Analysis-Power-BI)**<br>
*10K+ records · 4-table star schema*<br>
**Built for:** marketing managers reallocating campaign budget toward profitable channels, and product/merchandising managers deciding which SKUs to push.
- **Question:** Is marketing budget going to the campaigns and products that actually generate profit, not just revenue?
- **Approach:** Modeled a 4-table star schema to separate ads-driven from direct revenue and calculate Gross Margin ROAS by campaign, product, and channel.
- **Recommendation:** Reallocate budget from high-spend, unprofitable campaigns toward under-funded, higher-margin ones.

**[Sales Performance & Market Expansion for Global Superstore](https://github.com/maitruong-data/Sales-Performance-and-Market-Expansion-for-Global-Superstore-PowerBI)**<br>
*52K+ records · 3-table star schema*<br>
**Built for:** sales and expansion strategy leads deciding which markets to enter next, and category managers applying bundling and margin-protection tactics by product line.
- **Question:** Which markets and products should the business prioritize for expansion, and where is growth actually coming from?
- **Approach:** Built a star schema linking orders, returns, and sales-rep data, then used Pareto analysis to isolate the ~20% of products driving 80% of profit per market.
- **Recommendation:** Focus core growth investment on APAC, EU, and US; pilot expansion in EMEA, Africa, and Canada; apply category-specific bundling and margin-protection tactics.

────────────────────

### 🔄 End-to-End Projects

**[E-commerce Analytics Pipeline](https://github.com/maitruong-data/ecommerce-analytics-pipeline)**<br>
*~6M rows · 5 data sources · Python ETL → BigQuery → Power BI*<br>
**Built for:** marketing, finance, and risk managers deciding who to target for reactivation, how to report collections accurately, and where payment risk concentrates.
- **Question:** Which customer segments are most valuable or at risk, how much revenue is actually collected, and where is payment risk concentrated?
- **Approach:** Built an OOP Python ETL pipeline (extractor/transformer/loader pattern) moving 5 raw sources from GCS into a BigQuery warehouse and reporting layer, then built 3 Power BI dashboards on top.
- **Recommendation:** Fixed a payment-status bug that was counting Buy Now, Pay Later deposits and refunds as unpaid, correcting the collection rate from 40.87% to 59.11% and giving Finance a more accurate read on the business.

---

## 🚧 Work In Progress

**Sansaino Marketing Data Pipeline**<br>
Building a pipeline to centralize and structure sansaino's marketing data for reporting and analysis.

---

## 📫 Contact Me

<p>
  <a href="mailto:truongmain171@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/truong-mai"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
