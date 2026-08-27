# 📊 Marketing Analytics – Customer Engagement & Marketing Performance

_Analyzing customer engagement, customer journeys, reviews, and marketing performance to support data-driven marketing decisions using SQL, Python, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project evaluates customer engagement, marketing activities, customer journeys, and customer reviews to drive strategic insights for marketing and customer experience optimization. A complete analytics pipeline was built using SQL for data modeling, Python for customer review enrichment, and Power BI for visualization and reporting.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective marketing and customer engagement management are critical for improving customer experience and business performance. This project aims to:
- Identify factors impacting conversion rate and recommend improvements
- Determine which marketing content types drive the highest engagement
- Analyze customer reviews to surface recurring positive and negative themes
- Evaluate product and customer performance across the journey
- Identify opportunities to improve overall marketing effectiveness

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple datasets covering customers, products, customer journeys, customer reviews, and engagement data
- Dimension tables created for customers and products
- Fact tables created for customer journeys, reviews, and engagement
- Enriched customer review dataset created using Python

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL (Common Table Expressions, Joins, Filtering, Aggregations)
- Python (Pandas, Data Cleaning, Data Enrichment)
- Power BI (Interactive Visualizations, DAX)
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
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

- Created customer and product dimension tables
- Created fact tables for customer journey, customer reviews, and customer engagement
- Cleaned and prepared customer review data using Python
- Enriched customer review data for sentiment and rating analysis
- Created a calendar table using DAX for time-based analysis
- Prepared analysis-ready datasets for Power BI reporting

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Conversion Rate Trends:**
- Overall conversion rate rebounded to **10.2%** in December after dipping to **5.0%** in October
- Lowest overall conversion month: **May at 4.3%**, with no standout products
- Highest overall conversion month: **January at 18.5%**, driven by Ski Boots at a **150%** conversion rate

**Customer Engagement:**
- Views peaked in **February and July**, then declined from **August onward**
- Click-through rate stands at **15.37%**, indicating engaged users interact effectively despite lower overall click/like volume
- Blog content drove the most views, particularly in **April and July**; social media and video content maintained steady but slightly lower engagement

**Customer Review Distribution:**
- **140** reviews at 4 stars and **135** reviews at 5 stars — the majority of feedback
- **57** reviews at 2 stars and **26** reviews at 1 star
- Average rating holds steady at **3.7**, below the **4.0** target

**Sentiment Analysis:**
- **275** reviews carry positive sentiment vs. **82** negative
- Remaining reviews fall into mixed/neutral sentiment, representing a conversion opportunity

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Customer Engagement**: Which customers and marketing activities generate the highest engagement?
2. **Customer Journey**: How do customers interact across different stages of the customer journey?
3. **Product Performance**: Which products generate stronger customer engagement and feedback? (Ski Boots led January conversions at **150%**)
4. **Customer Reviews**: What insights emerge from **275** positive vs. **82** negative sentiment reviews?
5. **Marketing Performance**: Which marketing activities contribute most effectively to engagement, given a **15.37%** CTR?
6. **Customer Experience**: What areas need improvement to move the average rating from **3.7** to the **4.0** target?

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - Customer Engagement (views, clicks, likes by month)
  - Customer Journey Analysis
  - Product Performance & Conversion Rates
  - Customer Reviews & Sentiment Breakdown
  - Marketing Performance by Content Type
  - Key Performance Indicators (CTR: 15.37%, Avg. Rating: 3.7)

![image alt](https://github.com/samyakmda/marketing-analytics-sql-python-powerbi/blob/main/Images/dashboard.png)

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https://github.com/samyakmda/marketing-analytics-sql-python-powerbi.git
```
2. Create the required SQL tables:
```
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
```
fact_customer_reviews_enrich.csv
```
5. Open Power BI Dashboard:
```
Dashboard.pbix
```
6. Use the calendar DAX script for time-based analysis:
```
Calendar DAX Script.txt
```

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Target high-performing product categories (e.g., Ski Boots) with seasonal promotions during peak months like January
- Revitalize content strategy to reverse the post-August decline in views — prioritize blog content, which drove the most engagement in April and July
- Optimize call-to-action placement to lift click/like volume without losing the strong 15.37% CTR
- Build a feedback loop to convert mixed/neutral reviews into positive ones, closing the gap from 3.7 to the 4.0 rating target
- Follow up with dissatisfied customers (26 one-star, 57 two-star reviews) to resolve issues and encourage re-rating
- Use Power BI dashboards for continuous marketing performance monitoring

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Samyak Meshram**
Data Analyst
📧 Email: [samyakmda@gmail.com](mailto:samyakmda@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-mishra-30813b174/)
🔗 [Portfolio](https://www.youtube.com/@techclasses0810/)
