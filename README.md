# SEO-Traffic-Analysis
This project showcases my hands-on SQL practice with **analytical queries** on an e-commerce sales dataset.  
It covers beginner to moderate concepts, including **aggregations, joins, CTEs, and analytical insights** using window functions.  

---

## 📊 Dataset  
The dataset contains e-commerce product records with the following columns:  

- **Date** – Day of traffic record  
- **Keyword** – Search query driving traffic  
- **Page** – Landing page  
- **Impressions** – Times the page/keyword appeared in search results  
- **Clicks** – Number of clicks received  
- **CTR (Click Through Rate)** – Percentage of clicks per impression  
- **Position** – Average ranking position  

---

## 🚀 Features & Queries  

The repository includes SQL queries that solve **real-world SEO problems**:

### 🔑 Keyword Analysis  
- **Top Keywords by Clicks** – Identify keywords driving the most traffic.  
- **Top 5 Keywords with the Highest Impressions** – Find high-visibility queries.  
- **Keywords with More than 500 Clicks but CTR < 20%** – Highlight underperforming keywords.  
- **Top 5 Keywords by Total Clicks** – See your best performers.  
- **Keywords with CTR Above Overall Average** – Detect strong-performing keywords.  
- **Keywords with High Impressions but Low CTR (Missed Opportunities)** – Spot optimization opportunities.  
- **Top 5 Keywords with Best CTR but Low Impressions (Hidden Gems)** – Keywords worth scaling.  
- **Find Keywords Where Average Position < 5** – Track high-ranking queries.  
- **Keywords That Improved Over Time (First vs Last Position)** – Measure SEO growth.  

### 📄 Page-Level Analysis  
- **Pages with Highest CTR** – Pages converting impressions into clicks effectively.  
- **Pages with CTR Greater Than 10%** – Detect strong performers.  
- **Compare Performance of Pages (Impressions vs Clicks Ratio)** – Benchmark pages against each other.  
- **Top 5 Pages by CTR** – Highlight your most engaging pages.  
- **Average Position by Page** – Track visibility across keywords.  
- **Pages with Above-Average CTR** – Identify winning pages.  
- **Rank Pages by Clicks Each Month** – Track seasonal leaders.  

### 📈 Trend Analysis  
- **Traffic Trends Month-by-Month** – Understand growth.  
- **Keyword Performance Trend (Month by Month)** – Keyword-level seasonality.  
- **Monthly Click-Through Rate (CTR) Trend** – See user behavior changes.  
- **Daily Trend of CTR** – High-resolution performance tracking.  
- **Cumulative Clicks Over Time** – Long-term growth view.  
- **Cumulative CTR (Running Total)** – Progressive performance tracking.  
- **Calculate Monthly Growth in Clicks** – Measure improvement pace.  
- **Running Total of Clicks Over Time (Window Function)** – SEO snowball effect.  
- **Top 3 Pages by Total Clicks Each Month (Window Functions)** – Find leaders per month.  

---

## 🛠️ Tech Stack  

- **SQL** (queries written for practice; adaptable to MySQL, PostgreSQL, SQL Server)  
- **Dataset**: SEO/Google Search Console style dataset (keywords, pages, clicks, impressions, CTR, position, dates).  

---
