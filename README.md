# 📊 Marketing Analytics – Customer Engagement & Marketing Performance

*Analyzing customer engagement, customer journeys, reviews, and marketing performance to support data-driven marketing decisions using SQL, Python, and Power BI.*

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

This project evaluates customer engagement, marketing activities, customer journeys, and customer reviews to drive strategic insights for marketing and customer experience optimization. SQL was used for data modeling and analysis, Python for customer review enrichment, and Power BI for visualization and reporting.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective marketing and customer engagement management are critical for improving customer experience and business performance. This project aims to:

* Analyze customer engagement across marketing activities
* Understand customer journey and interaction patterns
* Analyze customer reviews and feedback
* Evaluate product and customer performance
* Identify opportunities to improve marketing effectiveness

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

* Multiple datasets covering customers, products, customer journeys, customer reviews, and engagement data
* Dimension tables created for customers and products
* Fact tables created for customer journeys, reviews, and engagement
* Enriched customer review dataset created using Python

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

* SQL (Common Table Expressions, Joins, Filtering, Aggregations)
* Python (Pandas, Data Cleaning, Data Enrichment)
* Power BI (Interactive Visualizations, DAX)
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

* Created customer and product dimension tables
* Created fact tables for customer journey, customer reviews, and customer engagement
* Cleaned and prepared customer review data using Python
* Enriched customer review data for further analysis
* Created a calendar table using DAX for time-based analysis
* Prepared analysis-ready datasets for Power BI reporting

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Customer Engagement Analysis:**

* Analyzed customer engagement and interaction patterns
* Evaluated engagement across different marketing activities
* Identified variations in customer engagement levels

**Customer Journey Analysis:**

* Analyzed customer interactions across different journey stages
* Examined customer behavior throughout the marketing journey

**Customer Review Analysis:**

* Enriched customer review data using Python
* Analyzed customer feedback and review patterns
* Evaluated product-level customer feedback

**Marketing Performance Analysis:**

* Compared marketing activities based on customer engagement
* Identified areas for improving marketing effectiveness

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Customer Engagement**: Which customers and marketing activities generate the highest engagement?

2. **Customer Journey**: How do customers interact across different stages of the customer journey?

3. **Product Performance**: Which products generate stronger customer engagement and feedback?

4. **Customer Reviews**: What insights can be identified from customer reviews and enriched review data?

5. **Marketing Performance**: Which marketing activities contribute most effectively to customer engagement?

6. **Customer Experience**: What areas of the customer journey and product experience require improvement?

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

* Power BI Dashboard shows:

  * Customer Engagement
  * Customer Journey Analysis
  * Product Performance
  * Customer Reviews
  * Marketing Performance
  * Key Performance Indicators

![image alt](https://github.com/samyakmda/marketing-analytics-sql-python-powerbi/blob/main/Images/dashboard.png)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:

```bash
git clone https://github.com/samyakmda/marketing-analytics-sql-python-powerbi.git
```

2. Create the required SQL tables:

```text
dim_customers.sql
dim_products.sql
fact_customer_journey.sql
fact_customer_reviews.sql
fact_engagement_data.sql
```

3. Run the customer review enrichment script:

```bash
python customer_reviews_enrichment.py
```

4. Open and review the enriched customer review dataset:

```text
fact_customer_reviews_enrich.csv
```

5. Open Power BI Dashboard:

```text
Dashboard.pbix
```

6. Use the calendar DAX script for time-based analysis:

```text
Calendar DAX Script.txt
```

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

* Focus marketing efforts on highly engaged customer segments
* Optimize customer journeys based on customer interaction patterns
* Use customer reviews to identify product and customer experience improvements
* Improve marketing activities based on engagement performance
* Monitor customer feedback to identify areas requiring attention
* Use Power BI dashboards for continuous marketing performance monitoring

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Samyak Meshram**
Data Analyst
📧 Email: [samyakmda@gmail.com](mailto:samyakmda@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-mishra-30813b174/)
🔗 [Portfolio](https://www.youtube.com/@techclasses0810/)
