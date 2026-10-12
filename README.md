# 👋 Hi, I'm Vijay Kumar

### Business Analytics | Data Analytics | BI

I am a **business professional with experience in Business Development, Sales, CRM, Manufacturing and Entrepreneurship**, now specializing in **Data Analytics, Business Intelligence and data-driven decision-making**.

I combine **business understanding with data and technology** to transform business problems into **measurable insights, actionable recommendations and business decisions**.

**Business Problem → Data → Analysis → Insight → Action**

📍 Bangalore, India  
💼 Assistant Manager – Business Development  
🎓 Pursuing **MS in Data Science through the Scaler–Woolf pathway**  
🎯 Target roles: **Data Analyst | Business Analyst | BI Analyst**

## 📫 Connect

- 🌐 Portfolio: [vijaybsbs.github.io](https://vijaybsbs.github.io/)
- 💼 LinkedIn: [Vijay Kumar](https://www.linkedin.com/in/vijaybsbs/)
- 💻 GitHub: [@vijaybsbs](https://github.com/vijaybsbs)

---

## 📊 Featured Analytics Projects

### 🇧🇷 Target Brazil E-commerce Analytics
**BigQuery / GoogleSQL / Looker Studio**

End-to-end e-commerce analytics covering data quality, customer behaviour, geography, order economics, payments, logistics, delivery performance, customer experience and RFM analysis.

**Selected findings & business implications**
- **97%** of active customers are one-time buyers; repeat customers represent only **3%** → retention initiatives should focus on converting one-time buyers into repeat customers.
- **48.85%** of customers account for **80%** of observed customer value → customer-value concentration can help prioritize retention and targeted engagement.
- São Paulo, Rio de Janeiro and Minas Gerais represent **61.24%** of recent high-value one-time customers → these markets provide a clear geographic focus for retention and cross-sell initiatives.
- **80.82%** of recent high-value one-time orders contain a single item → cross-sell and basket-expansion opportunities should be investigated for high-value one-time customers.

**Key skills:** SQL • BigQuery • Data Modelling • CTEs • Window Functions • RFM • KPI Analysis • Dashboarding

🔗 [View Project](https://github.com/vijaybsbs/Target-Brazil-Ecommerce-Analytics)

---

### 🧸 Maven Toys Retail Sales & Inventory Optimization
**BigQuery / GoogleSQL / Looker Studio**

Retail sales and inventory analysis across **50 stores and 35 products**, covering revenue, cost, product performance, store performance, pricing, inventory risk and Pareto analysis.

**Selected findings & business implications**
- **$14.44M revenue**, **$4.01M gross profit** and **27.79% gross margin**.
- The top **15 of 35 products (43%) generate approximately 80.08% of revenue** → revenue is concentrated, but not at a classic 80/20 level; availability and replenishment of these high-contribution products deserve priority.
- Toys is the largest revenue category at **35.26%**, while Electronics has the highest gross margin at **44.57%** → category strategy should balance revenue scale with margin contribution.
- **157 store-product combinations have no inventory record**, while **7 duplicate inventory rows** require data-quality attention → inventory decisions should account for incomplete and duplicated inventory records.
- **3 inventory records have stock despite no historical sales** → these combinations warrant review for assortment fit, local demand or potential overstock.

**Key skills:** SQL • Window Functions • Ranking • Pareto Analysis • Retail Analytics • Inventory Analysis • Dashboarding

🔗 [View Project](https://github.com/vijaybsbs/Maven-Toys-Retail-Sales-Inventory-Optimization)

---

### 🚲 Yulu Bike Rental Demand & Hypothesis Testing
**Python / EDA / Statistics**

Bike rental demand analysis using exploratory data analysis and statistical hypothesis testing to evaluate the impact of working days, seasons, weather and environmental factors on demand.

**Statistical findings**
- **Working days:** independent 2-sample t-test → **t = 1.210, p = 0.2264** → no statistically significant difference in average rentals between working and non-working days.
- **Season:** one-way ANOVA → **F = 236.95, p = 6.16 × 10⁻¹⁴⁹** → rental demand differs significantly across seasons; Fall has the highest median and Spring the lowest in the analysis.
- **Weather:** one-way ANOVA → **F = 65.53, p = 5.48 × 10⁻⁴²** → rental demand differs significantly across weather conditions; clear weather has the highest median, while light snow has the lowest.
- **Season × Weather:** chi-square test → **χ² = 46.10, df = 6, p = 2.83 × 10⁻⁸** after excluding the single heavy-rain observation because the original expected-frequency assumption was violated → season and weather are statistically associated.

**Business implication:** demand planning should account for **season and weather conditions** rather than treating working-day status alone as a significant demand driver.

**Key skills:** Python • Pandas • EDA • Statistics • Hypothesis Testing • Business Analytics

🔗 [View Project](https://github.com/vijaybsbs/Yulu-Bike-Rental-Demand-Hypothesis-Testing-and-Business-Analytics)

---

### 🍷 Australian Wine Company Insights
**Tableau**

Interactive business intelligence dashboard focused on sales performance, revenue targets, regional performance, freight costs, product-segment trends and customer retention.

**Selected findings & business implications**
- **Revenue reached 9.24M against a 9.751M target**, representing approximately **94.8% target achievement** → the business was below its revenue target by about **0.51M** in the dashboard period.
- **Order quantity was 129,284 against a target of 372,420**, representing approximately **34.7% target achievement** → quantity performance shows a substantial gap relative to the target.
- The dashboard reports an **average discount of 4.96%**, **freight expense of 119,699** and an **average unit price of 88**, providing a basis for monitoring pricing, discounting and logistics costs together.
- Regional revenue varies materially across the states shown in the dashboard, including **South Australia (962,572)**, **Tasmania (795,403)** and **Northern Territory (514,268)** → regional performance can be compared to identify differences in revenue contribution.
- Revenue trends vary across wine segments over time: **Red Wine shows a relatively consistent pattern**, while **Rose/Sparkling Wine shows greater volatility** and **White Wine records a pronounced revenue spike around 2012**.
- Order quantity increases across the displayed years, rising from approximately **25K in 2010 to 42K in 2013** → the dashboard indicates increasing order volume over the period.
- The customer retention view shows a growing contribution from customers associated with earlier ordering periods over time, providing a basis for monitoring **repeat-order behaviour and customer retention**.

**Business focus:** revenue performance • target tracking • regional analysis • wine-segment trends • freight analysis • customer retention

🔗 [View Tableau Project](https://public.tableau.com/views/AustralianWineCompanyInsightsDashboard_17593967646220/AustralianWineCompanyInsightsDashboard)

---

### 🍽️ Zomato Restaurant Market Analysis
**SQL + Python / Pandas + Power BI / DAX**

An end-to-end restaurant analytics case study covering SQL business questions, exploratory data analysis, data-quality validation, Python-based cleaning and feature engineering, and a six-page Power BI dashboard.

The project evolved through three phases: SQL analysis → Python EDA → corrected analysis and interactive BI reporting. Deeper investigation uncovered rating placeholders and sampling limitations that changed several earlier conclusions.

**Selected findings & business implications**

- **90.59% of the original 9,551 records are from India** (8,652 restaurants). Because the dataset mixes countries and contains inconsistent currency labels, the final pricing and market analysis focuses on India.
- **Data quality changed the rating story:** 2,139 Indian restaurants with fewer than four votes had a placeholder rating of 1.0. Treating these as *not rated yet* raised the average Indian rating from **2.77 to 3.35**.
- **City comparisons required a sampling check:** 28 Indian cities had exactly 20 listings. The final analysis restricts city-level comparisons to cities with at least 100 restaurants, avoiding misleading conclusions from small samples.
- **Delhi NCR accounts for 92% of India's listed restaurants** (7,947 of 8,652), with New Delhi alone contributing 63%—highlighting the dataset's strong geographic concentration.
- **Price and ratings:** cleaned average ratings rise from **3.20 in Budget to 3.74 in Luxury**, but the difference between Premium and Luxury is only 0.06 rating points, despite roughly twice the cost.
- **Delivery opportunity:** 64% of restaurants offer neither online delivery nor table booking. Gurgaon leads the qualifying city comparisons on delivery adoption at **38.0%**, while New Delhi's scale suggests a substantial potential delivery gap.

**Power BI dashboard:** Six pages covering dataset scope, data quality, market overview, ratings and engagement, price and value, and delivery and services.

**Key skills:** SQL • Python • Pandas • Data Cleaning • Feature Engineering • EDA • Power BI • DAX • Data Modelling • Business Analytics

🔗 [View Project & Dashboard](https://github.com/vijaybsbs/Zomato-Restaurant-Business-Analysis)

📄 [View 6-Page Power BI Dashboard (PDF)](https://github.com/vijaybsbs/Zomato-Restaurant-Business-Analysis/blob/main/Powerbi/Zomato%20Powerbi%20-%20pdf.pdf)

---

### 🚚 Delhivery Logistics Data Analysis & Feature Engineering
**Python / Pandas**

Logistics data analysis and feature engineering to transform trip-level operational data into model-ready features for route, delivery and performance analysis.

**Selected findings & business implications**
- **144,867 operational records** represent **14,817 unique trips** across approximately **27 days** of data.
- Average **actual trip time is 417 minutes vs 214 minutes estimated by OSRM** → actual operations take substantially longer than routing estimates on average, making estimate-vs-actual gaps important for operational planning.
- Average **actual distance is 234 km vs 285 km OSRM estimated distance** → routing distance and observed operational distance differ materially and should be evaluated separately rather than treated as interchangeable measures.
- The dataset contains **1,500+ source/destination logistics centers**, providing a broad geographic basis for route and hub-level analysis.
- **293 source-name and 261 destination-name values were missing** before preprocessing, representing less than **0.3%** of the 144,867 records; no duplicate records were identified.

**Business focus:** trip-level grain • route performance • actual vs estimated distance/time • operational feature engineering

**Key skills:** Python • Pandas • Data Cleaning • Feature Engineering • Operational Analytics

🔗 [View Project](https://github.com/vijaybsbs/Delhivery-Logistics-Data-Analysis-and-Feature-Engineering)

---

## 🔎 Core Business & Data Skills

### Business Analytics
Sales • Revenue Analysis • CRM Analytics • Customer Analytics • Lead Funnel Analysis • Market Analysis • KPI Reporting

### Data Analytics
SQL • GoogleSQL • BigQuery • Python • Pandas • Excel • Exploratory Data Analysis • Statistics

### Business Intelligence
Tableau • Looker Studio • Dashboarding • KPI Analysis • Data Visualization

### AI
Generative AI • Prompt Engineering • AI-assisted Analytics

### Tools
Git • GitHub • Google Colab • Jupyter • Google Sheets

---

## 💼 Business + Data Experience

My career sits at the intersection of **business, sales, data and technology**.

I bring practical experience across **Business Development, Sales, CRM, Revenue Analysis, Manufacturing and Entrepreneurship**, with a growing focus on data-driven decision-making.

### Commercial & CRM Analytics

- Sales and revenue performance analysis; CRM activity and lead-funnel analytics
- Daily sales productivity, KPI tracking and performance dashboards
- Created a lead generation → nurture → conversion SOP supported by daily sales reporting

### Business Development & Stakeholder Management

- Architect, builder and dealer/channel engagement; project and specification business
- Cross-functional coordination with marketing and sales teams
- Conducted knowledge-sharing / L&L sessions for design and execution teams

### Data-Driven Approach

I use **SQL, Python, Excel, BigQuery and BI tools** to connect business questions with data and translate analysis into actionable business insights.

**Business Problem → Data → Analysis → Insight → Action**

---

## 🎓 Education & Professional Learning

### MS in Data Science — Scaler × Woolf *(in progress)*

I am pursuing a **Master of Science (MS) in Data Science** through the Scaler learning pathway, with the academic degree awarded by **Woolf Higher Education Institution**.

**Core Areas:**  
Data Analytics • Statistics • SQL • Python • Machine Learning • Data Visualisation • Business Intelligence • Applied Data Science

### 🤖 Introduction to Advanced Business Analytics with AI — Oxford Saïd

**Saïd Business School, University of Oxford**

Completed the **Introduction to Advanced Business Analytics with AI** course, focused on applying business analytics and AI to data-driven decision-making, strategic and operational outcomes, and responsible AI adoption.

**Key Areas:**  
Business Analytics • Generative AI • AI for Decision-Making • Predictive & Prescriptive Analytics • AI Risk & Ethics • Real-World Case Studies

- **Completed:** August 2026
- **Academic Credit:** 1 credit
- **Credential:** University of Oxford, Saïd Business School

### 🎓 Master of Business Administration (MBA) — Mysore University

**Business Management • Strategy • Marketing • Operations • Entrepreneurship**

### 🎓 Bachelor of Engineering (B.E.) — Mechatronics

---

## 📚 Currently Learning

- Advanced SQL and analytical problem solving
- Python for data science and applied analytics
- Statistics and applied data analysis
- Generative AI and LLM applications
- AI-assisted business analytics

---

## 🎯 What I'm Looking For

I am interested in opportunities where I can combine **business understanding, analytics and technology** to solve real-world business problems.

**Primary:** Data Analyst • Business Analyst • BI Analyst

**Growth Areas:** Business Analytics • Applied Analytics • Data Science • AI & Analytics

---
