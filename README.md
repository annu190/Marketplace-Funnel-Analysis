# 📊 Marketing Funnel & ROI Analytics Dashboard

### Analyzing Marketing Performance Across Channels, Campaigns & Time

An end-to-end **Marketing Analytics / Business Analytics** project that analyzes marketing funnel performance across multiple channels and campaigns using **Excel, Python, Power BI and DAX**.

The project evaluates the complete marketing journey from **impressions → clicks → leads → conversions → revenue**, while measuring campaign efficiency through **CTR, CPC, CPL, Conversion Rate, CAC and ROI**.

An interactive Power BI dashboard was developed to provide a consolidated view of marketing performance by **channel, campaign and month**, supporting data-driven marketing analysis and business decision-making.

---

## 👨‍💻 Project Information

| Category | Details |
|---|---|
| **Project Type** | Business Analytics / Marketing Analytics |
| **Domain** | Marketing Analytics |
| **Tools** | Excel, Python, Power BI, DAX |
| **Python Libraries** | Pandas, NumPy |
| **Dataset Size** | 1,000 records |
| **Number of Columns** | 15 |
| **Marketing Channels** | 5 |
| **Campaigns** | 10 |
| **Time Period** | January 2025 – August 2026 |
| **Currency** | INR |

---

# 🎯 Project Objective

The primary objective of this project is to evaluate marketing funnel and campaign performance using data-driven analysis and develop an interactive dashboard that enables stakeholders to monitor marketing efficiency and identify opportunities for optimization.

### Specific Objectives

- Analyze marketing funnel performance
- Evaluate channel-level performance
- Analyze campaign performance
- Measure marketing efficiency
- Analyze revenue trends over time
- Develop an interactive Power BI dashboard
- Generate actionable business insights

---

# 💼 Business Problem

Marketing teams often work with data from multiple campaigns and channels, making it difficult to obtain a consolidated view of overall marketing performance.

Simply measuring impressions, clicks or leads does not provide a complete picture of campaign effectiveness. Businesses also need to understand:

- Which channels generate revenue?
- Which channels provide higher ROI?
- Which channels have lower customer acquisition cost?
- Which campaigns generate more leads and conversions?
- How efficiently are prospects moving through the marketing funnel?
- How does marketing performance change over time?
- Where are potential opportunities for optimization?

This project addresses these questions by combining marketing funnel metrics, financial performance indicators and interactive data visualization into a single analytical solution.

---

# 📁 Dataset

The project uses a structured marketing dataset containing **1,000 records** of marketing campaign activity covering **January 2025 to August 2026**.

The dataset includes performance information across **5 marketing channels and 10 campaigns**.

### Marketing Channels

- Google Ads
- Meta Ads
- Instagram
- Facebook
- Email Marketing

### Campaigns

- Summer Sale
- Festive Offers
- New Product Launch
- Brand Awareness
- Lead Generation
- Monsoon Campaign
- Diwali Promotion
- Year-End Sale
- Retargeting Campaign
- Customer Acquisition

### Dataset Fields

| Field | Description |
|---|---|
| Date | Marketing activity date |
| Campaign | Campaign name |
| Channel | Marketing channel |
| Impressions | Number of impressions |
| Clicks | Number of clicks |
| Ad Spend (INR) | Marketing expenditure |
| Leads | Number of generated leads |
| Conversions | Number of conversions |
| Revenue (INR) | Revenue generated |
| CTR (%) | Click-through rate |
| CPC (INR) | Cost per click |
| CPL (INR) | Cost per lead |
| Conversion Rate (%) | Lead-to-conversion rate |
| CAC (INR) | Customer acquisition cost |
| ROI (%) | Return on investment |

---

# 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Excel** | Dataset inspection, organization and validation |
| **Python** | Data cleaning, validation, KPI calculation and analysis |
| **Pandas** | Data manipulation, grouping and aggregation |
| **NumPy** | Numerical calculations |
| **Google Colab** | Python analysis environment |
| **Power BI** | Interactive dashboard and data visualization |
| **DAX** | Dynamic KPI and analytical measures |

### Analytical Workflow
Excel
   ↓
Data Inspection & Validation
   ↓
Python / Pandas / NumPy
   ↓
Data Cleaning & KPI Validation
   ↓
Channel & Campaign Analysis
   ↓
Power BI + DAX
   ↓
Interactive Dashboard
   ↓
Insights & Business Recommendations
---

# 📐 KPI Calculations

The project evaluates marketing performance using the following key performance indicators:

| KPI | Formula | Purpose |
|---|---|---|
| **CTR (%)** | Clicks / Impressions × 100 | Measures the percentage of impressions that resulted in clicks |
| **CPC (INR)** | Ad Spend / Clicks | Measures the average cost per click |
| **CPL (INR)** | Ad Spend / Leads | Measures the average cost per generated lead |
| **Conversion Rate (%)** | Conversions / Leads × 100 | Measures the percentage of leads converted |
| **CAC (INR)** | Ad Spend / Conversions | Measures the average acquisition cost per conversion |
| **ROI (%)** | (Revenue − Ad Spend) / Ad Spend × 100 | Measures return generated relative to marketing spend |

---

# 🧹 Data Cleaning & Preparation

The dataset was prepared and validated before analysis.

### Data Preparation Steps

- Loaded the marketing dataset into Python using Pandas
- Inspected dataset structure, dimensions and column names
- Converted the Date field into the appropriate date format
- Checked for missing values
- Checked for duplicate records
- Validated numerical fields for negative or invalid values
- Validated categorical fields such as Channel and Campaign
- Recalculated key marketing KPIs
- Compared calculated KPI values with the existing dataset metrics
- Prepared the validated dataset for analysis and visualization

---

# 🔎 Exploratory Data Analysis

Exploratory analysis was performed to understand marketing performance across different dimensions.

### Areas Analyzed

- Overall marketing performance
- Channel-level revenue and ROI
- Channel-level leads and customer acquisition cost
- Campaign-level performance
- Revenue trends over time
- Marketing funnel movement
- Conversion efficiency
- Customer acquisition efficiency

The analysis was used to identify performance patterns and areas requiring further investigation.

---

# 📊 Power BI Dashboard

An interactive **Marketing Funnel & ROI Analytics Dashboard** was developed using Microsoft Power BI.

### Dashboard Components

- Total Spend
- Total Leads
- Total Conversions
- Total Revenue
- Overall ROI
- Marketing Funnel
- Revenue by Channel
- ROI by Channel
- Monthly Revenue Trend
- Campaign Performance Table
- Date filter
- Channel filter
- Campaign filter

### Dashboard Preview

![Marketing Funnel & ROI Analytics Dashboard](Screenshots/dashboard.png)

**Figure: Marketing Funnel & ROI Analytics Dashboard developed using Microsoft Power BI**

---

# 📈 Key Results

The dashboard provides the following overall marketing performance results:

| Metric | Result |
|---|---:|
| **Total Marketing Spend** | ₹4.89M |
| **Total Leads** | 125.74K |
| **Total Conversions** | 10,844 |
| **Total Revenue** | ₹35.18M |
| **Overall ROI** | 619.40% |

### Marketing Funnel

Impressions
25,300,319
      ↓
Clicks
1,197,289
      ↓
Leads
125,740
      ↓
Conversions
10,844
📊 Channel Performance
The dashboard recorded the following channel-level revenue and ROI results:
Channel	Revenue	ROI
Email Marketing	₹16.0M	1427.56%
Google Ads	₹7.4M	544.33%
Meta Ads	₹4.9M	399.17%
Instagram	₹4.5M	336.82%
Facebook	₹2.4M	248.95%


Email Marketing recorded the highest revenue and ROI among the channels represented in the dashboard.
📋 Campaign Performance
Selected campaign-level results visible in the dashboard include:
Campaign	Spend	Leads	Conversions	Revenue	ROI	CAC
Festive Offers	₹4,90,742.39	12,225	1,028	₹33,02,162.83	572.89%	₹477.38
Brand Awareness	₹4,03,315.66	10,358	867	₹27,21,412.40	574.76%	₹465.19
New Product Launch	₹4,19,172.81	10,754	901	₹28,98,987.47	591.60%	₹465.23
Monsoon Campaign	₹6,12,903.65	15,714	1,363	₹43,43,799.41	608.72%	₹449.67


💡 Key Insights
Based on the analysis and dashboard results:
- The overall marketing program generated ₹35.18M in revenue from ₹4.89M in marketing spend.
- The overall recorded ROI was 619.40%.
- The marketing funnel generated 1,197,289 clicks from 25,300,319 impressions.
- The funnel subsequently generated 125,740 leads and 10,844 conversions.
- Email Marketing recorded the highest revenue among the channels represented in the dashboard.
- Email Marketing also recorded the highest ROI at 1427.56%.
- Google Ads generated the second-highest channel revenue at approximately ₹7.4M.
- Channel-level ROI varied considerably, indicating differences in marketing efficiency across channels.
- Campaign-level results showed variation in revenue, conversions, ROI and CAC.
- Monthly revenue showed variation over the analysis period, indicating changes in marketing performance over time.
💼 Business Recommendations
Based on the analytical findings, the following areas can be considered for marketing optimization:
1. Evaluate Budget Allocation
Marketing budget allocation can be reviewed using ROI, revenue contribution and CAC together rather than relying on a single metric.
2. Investigate High-ROI Channel Strategies
The performance of Email Marketing can be examined further to understand the strategies contributing to its recorded ROI and determine whether similar approaches can be applied elsewhere.
3. Monitor Customer Acquisition Cost
Channels and campaigns with relatively higher CAC can be investigated to identify opportunities for improving acquisition efficiency.
4. Improve Lower-Funnel Performance
The movement from leads to conversions can be monitored closely to identify opportunities for improving conversion efficiency.
5. Analyze Campaign-Level Performance
Campaign performance should be reviewed using multiple KPIs including leads, conversions, revenue, CAC and ROI.
6. Monitor Monthly Performance
Monthly revenue and performance trends can be tracked continuously to identify significant changes and investigate the factors associated with them.
7. Establish Continuous Performance Monitoring
A recurring dashboard-based reporting process can help marketing teams monitor campaign performance and make data-driven decisions.
🐍 Python Analysis
Python was used for data inspection, validation, KPI recalculation and exploratory analysis.
Python Workflow
Load Dataset
      ↓
Inspect Structure
      ↓
Validate Data
      ↓
Clean & Prepare Data
      ↓
Calculate KPIs
      ↓
Analyze Channels
      ↓
Analyze Campaigns
      ↓
Evaluate Revenue & ROI

Python Analysis Preview
 
KPI Analysis Preview
 
🧠 Skills Demonstrated
This project demonstrates practical skills in:
- Marketing Analytics
- Business Analytics
- Data Analysis
- Data Cleaning
- Exploratory Data Analysis
- KPI Development
- Marketing Funnel Analysis
- ROI Analysis
- Customer Acquisition Cost Analysis
- Excel
- Python
- Pandas
- NumPy
- Power BI
- DAX
- Data Visualization
- Business Insights
- Data-driven Decision Making
📁 Project Structure
Marketing-Funnel-ROI-Analytics/
│
├── Dataset/
│   └── Marketing_Funnel_ROI_Analytics_Dataset_1000_Rows.xlsx
│
├── Python/
│   └── Marketing_Funnel_ROI_Analysis.ipynb
│
├── PowerBI/
│   └── Marketing_Funnel_ROI_Dashboard.pbix
│
├── Dashboard/
│   └── Marketing_Funnel_ROI_Dashboard.pdf
│
├── Documentation/
│   └── Marketing_Funnel_ROI_Analytics_Case_Study.pdf
│
├── Screenshots/
│   ├── dashboard.png
│   ├── python-analysis.png
│   └── kpi-analysis.png
│
└── README.md

🔄 End-to-End Project Workflow
Raw Marketing Dataset
        ↓
Excel Data Inspection
        ↓
Data Validation & Preparation
        ↓
Python Analysis
        ↓
KPI Calculation & Validation
        ↓
Channel & Campaign Analysis
        ↓
Power BI + DAX
        ↓
Interactive Dashboard
        ↓
Key Insights
        ↓
Business Recommendations

⚠️ Project Limitations
The analysis has several limitations:
1. Dataset Scope
The project uses a structured dataset containing 1,000 records and does not represent every possible real-world marketing activity.
2. Limited Marketing Variables
The dataset does not include additional customer-level variables such as demographics, customer lifetime value or detailed audience segments.
3. Attribution Limitations
The analysis does not implement multi-touch attribution. Revenue is analyzed using the available campaign and channel information.
4. External Factors
External factors such as seasonality, competitor activity, market conditions and changes in consumer behavior are not directly incorporated into the dataset.
5. Causality
The analysis identifies patterns and relationships in the available data but does not establish causal relationships between marketing activities and business outcomes.
🚀 Future Scope
The project can be extended into a more advanced marketing analytics solution through:
- Customer segmentation
- Customer Lifetime Value analysis
- Multi-touch marketing attribution
- Predictive analytics
- Revenue forecasting
- Campaign performance prediction
- Marketing budget optimization
- Real-time dashboard integration
- Automated reporting
- Advanced customer-level analytics
These extensions could help evolve the project from descriptive marketing analytics toward predictive and prescriptive analytics.
📚 Documentation
The complete project methodology, analysis, results, recommendations and limitations are documented in the project case study.
Case Study:
Documentation/Marketing_Funnel_ROI_Analytics_Case_Study.pdf
The case study covers:
- Project Overview
- Business Problem
- Project Objectives
- Dataset Description
- Tools & Technologies
- KPI Calculations
- Data Cleaning & Preparation
- Exploratory Data Analysis
- Power BI Dashboard Development
- Python Analysis
- Analysis Results & Key Insights
- Business Recommendations
- Project Conclusion
- Limitations & Future Scope
- End-to-End Project Methodology
👨‍💻 Author
Vishal Kamble
MBA – Marketing & IT
BBA – Marketing & HR
Focus Areas:
Marketing Analytics | Business Analytics | Digital Marketing | Data Visualization
📌 Project Summary
This project demonstrates an end-to-end approach to marketing analytics by combining Excel, Python, Pandas, NumPy, Power BI and DAX to analyze marketing funnel performance, campaign efficiency, revenue generation, customer acquisition cost and return on investment.
The project transforms structured marketing data into analytical insights and an interactive dashboard that can support data-driven marketing performance evaluation and business decision-making.
