# DataAnalystPortfolioProject_PBI_SQL_Python_MarketingAnalytics
# 📊 Marketing Analytics – Customer Engagement & Campaign Performance

*Analyzing customer engagement, journey behavior, reviews, and marketing performance using SQL, Python, and Power BI.*

---

## 📌 Table of Contents

* <a href="#overview">Overview</a>
* <a href="#business-problem">Business Problem</a>
* <a href="#dataset">Dataset</a>
* <a href="#tools--technologies">Tools & Technologies</a>
* <a href="#project-structure">Project Structure</a>
* <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
* <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
* <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
* <a href="#dashboard">Dashboard</a>
* <a href="#how-to-run-this-project">How to Run This Project</a>
* <a href="#final-recommendations">Final Recommendations</a>
* <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes customer engagement, marketing journeys, customer reviews, and product performance to generate actionable insights for marketing and business decisions. SQL was used for data modeling and analysis, Python for customer review enrichment and data processing, and Power BI for interactive visualization.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Understanding customer behavior and marketing performance is essential for improving customer engagement and optimizing marketing strategies. This project aims to:

* Analyze customer engagement across marketing channels
* Evaluate customer journey and interaction patterns
* Analyze customer reviews and sentiment
* Identify products and customer segments driving engagement
* Measure marketing performance and campaign effectiveness
* Support data-driven marketing and customer experience decisions

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

The project uses multiple datasets covering different aspects of the marketing analytics process:

* Customer dimension data
* Product dimension data
* Customer journey data
* Customer review data
* Customer engagement data
* Enriched customer review data

SQL fact and dimension tables were created to organize the data for analysis and reporting.

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

* SQL (Joins, CTEs, Aggregations, Data Modeling)
* Python (Pandas, Data Cleaning, Text Processing)
* Power BI (Interactive Dashboards, DAX)
* GitHub

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```text
marketing-analytics-sql-python-powerbi/
│
├── README.md
├── Calendar DAX Script.txt
├── Dashboard.pbix
├── Marketing Analytics Business Case (Clean).pptx
├── Presentation Example.pptx
├── PortfolioProject_MarketingAnalytics.bak
│
├── customer_reviews_enrichment.py
├── fact_customer_reviews_enrich.csv
│
├── dim_customers.sql
├── dim_products.sql
├── fact_customer_journey.sql
├── fact_customer_reviews.sql
└── fact_engagement_data.sql
```

---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

* Structured customer and product data into dimension tables
* Created fact tables for customer journeys, reviews, and engagement
* Cleaned and prepared customer review data using Python
* Enriched customer reviews for further analysis
* Prepared analysis-ready datasets for Power BI
* Created a calendar table using DAX for time-based analysis

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

The analysis focused on understanding:

* Customer engagement and interaction patterns
* Customer journey behavior across marketing touchpoints
* Customer review trends and sentiment
* Product-level performance
* Marketing channel effectiveness
* Relationship between customer engagement and business performance

SQL was used to combine and aggregate the underlying data, while Python was used for customer review enrichment and data preparation.

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Customer Engagement**: Which customers and marketing activities generate the highest engagement?

2. **Customer Journey**: How do customers interact across different stages of the marketing journey?

3. **Product Performance**: Which products receive stronger customer engagement and feedback?

4. **Customer Reviews**: What patterns can be identified from customer reviews and enriched review data?

5. **Marketing Performance**: Which marketing activities and channels contribute most effectively to customer engagement?

6. **Customer Experience**: What areas of the customer journey and product experience require improvement?

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

The Power BI Dashboard provides interactive analysis of:

* Customer Engagement
* Customer Journey Performance
* Product Performance
* Customer Reviews
* Marketing Performance
* Key Business KPIs

![image alt](https://github.com/samyakmda/marketing-analytics-sql-python-powerbi/blob/main/Images/dashboard.png)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:

```bash
git clone https://github.com/samyakmda/marketing-analytics-sql-python-powerbi.git
```

2. Set up the SQL tables using:

```text
dim_customers.sql
dim_products.sql
fact_customer_journey.sql
fact_customer_reviews.sql
fact_engagement_data.sql
```

3. Run the Python review enrichment script:

```bash
python customer_reviews_enrichment.py
```

4. Open and review the generated/enriched customer review data:

```text
fact_customer_reviews_enrich.csv
```

5. Open the Power BI Dashboard:

```text
Dashboard.pbix
```

6. Use the DAX calendar script when setting up the Power BI date table:

```text
Calendar DAX Script.txt
```

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

* Focus marketing efforts on high-engagement customer segments
* Optimize customer journeys based on engagement patterns
* Use customer reviews to identify product and experience improvement opportunities
* Prioritize marketing channels that generate stronger customer engagement
* Monitor product-level customer feedback regularly
* Use Power BI dashboards for continuous marketing performance monitoring

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Samyak Meshram**
Data Analyst
📧 Email: [samyakmda@gmail.com](mailto:samyakmda@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-mishra-30813b174/)
🔗 [Portfolio](https://www.youtube.com/@techclasses0810/)

