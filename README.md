# Marketplace Funnel & ROI Analytics Dashboard

> **Marketing Analytics | Business Intelligence | Power BI | Python**

An end-to-end marketing analytics project exploring funnel performance, campaign efficiency, revenue, and return on investment across marketing channels. The project combines Excel, Python, Pandas, NumPy, Power BI, and DAX to turn structured campaign data into an interactive dashboard and business-focused insights.

**Analysis period:** January 2025 – August 2026  
**Dataset:** 1,000 records · 5 channels · 10 campaigns  
**Currency:** INR

---

## 📌 Project at a Glance

| Area | Details |
|---|---|
| Project type | Marketing & Business Analytics |
| Core tools | Excel, Python, Power BI, DAX |
| Python libraries | Pandas, NumPy |
| Dashboard | Interactive Power BI report |
| Focus | Funnel analysis, channel and campaign performance, ROI, CAC |

## 🎯 Business Problem

Marketing teams need more than impressions, clicks, or leads to understand campaign effectiveness. They need a consolidated view of how prospects move through the funnel and how marketing spend relates to conversions and revenue.

This project explores questions such as:

- Which channels contribute the most revenue and ROI?
- How do customer acquisition costs vary across channels and campaigns?
- Which campaigns generate leads and conversions?
- Where do prospects drop off in the marketing funnel?
- How does performance change over time?

The analysis brings funnel metrics and financial KPIs together in a single dashboard to support performance review and further investigation.

## 🧭 Objectives

- Assess marketing funnel performance from impressions through conversions.
- Compare channel and campaign performance using consistent KPIs.
- Examine revenue, ROI, and customer acquisition cost.
- Explore monthly trends and differences in campaign efficiency.
- Build an interactive Power BI dashboard for slicing results by date, channel, and campaign.
- Translate the analysis into practical areas for further investigation.

## 📂 Dataset

The project uses a structured dataset of 1,000 records covering January 2025 through August 2026, across five marketing channels and ten campaigns.

### Channels

Google Ads · Meta Ads · Instagram · Facebook · Email Marketing

### Campaigns

Summer Sale · Festive Offers · New Product Launch · Brand Awareness · Lead Generation · Monsoon Campaign · Diwali Promotion · Year-End Sale · Retargeting Campaign · Customer Acquisition

### Fields

| Field | Description |
|---|---|
| Date | Date of marketing activity |
| Campaign / Channel | Campaign and channel identifiers |
| Impressions / Clicks | Reach and engagement volume |
| Ad Spend (INR) | Marketing expenditure |
| Leads / Conversions | Funnel outcomes |
| Revenue (INR) | Revenue recorded |
| CTR, CPC, CPL | Engagement and cost-efficiency metrics |
| Conversion Rate | Share of leads that converted |
| CAC | Acquisition cost per conversion |
| ROI | Return relative to marketing spend |

## 🛠️ Tools & Technologies

| Tool | Role in the project |
|---|---|
| Microsoft Excel | Dataset inspection and organization |
| Python | Data preparation, validation, KPI recalculation, and analysis |
| Pandas | Data manipulation, grouping, and aggregation |
| NumPy | Numerical calculations |
| Google Colab | Python analysis environment |
| Power BI | Interactive reporting and visualization |
| DAX | Measures and dynamic KPI calculations |

## 🔄 Workflow

```text
Excel Dataset
     ↓
Inspection and Validation
     ↓
Python: Cleaning, Preparation, and KPI Checks
     ↓
Exploratory Analysis by Channel and Campaign
     ↓
Power BI + DAX
     ↓
Interactive Dashboard
     ↓
Insights and Areas for Further Investigation
```

##  KPI Definitions

| KPI | Calculation | What it measures |
|---|---|---|
| CTR (%) | Clicks ÷ Impressions × 100 | Share of impressions that resulted in clicks |
| CPC (INR) | Ad Spend ÷ Clicks | Average cost per click |
| CPL (INR) | Ad Spend ÷ Leads | Average cost per lead |
| Conversion Rate (%) | Conversions ÷ Leads × 100 | Share of leads that converted |
| CAC (INR) | Ad Spend ÷ Conversions | Average acquisition cost per conversion |
| ROI (%) | (Revenue − Ad Spend) ÷ Ad Spend × 100 | Return relative to marketing spend |

##  Data Preparation & Analysis

The dataset was prepared for analysis using Python and Pandas. The documented preparation steps include:

- Inspecting dataset dimensions, structure, and column names.
- Converting the date field to a suitable date format.
- Checking missing values and duplicate records.
- Reviewing numerical fields for negative or invalid values.
- Validating categorical fields such as channel and campaign.
- Recalculating KPIs and comparing them with the dataset's existing metrics.
- Preparing the data for exploratory analysis and visualization.

Exploratory analysis covered overall performance, channel and campaign revenue/ROI, leads, CAC, funnel movement, conversion efficiency, and revenue trends over time.

## 📊 Power BI Dashboard

The interactive dashboard consolidates key marketing metrics and provides filters for date, channel, and campaign.

### Dashboard includes

- KPI cards: total spend, leads, conversions, revenue, and overall ROI
- Marketing funnel
- Revenue and ROI by channel
- Monthly revenue trend
- Campaign performance table
- Date, channel, and campaign filters

### Preview

![Marketing Funnel & ROI Analytics Dashboard](Screenshots/dashboard.png)

*Marketing Funnel & ROI Analytics Dashboard developed in Power BI.*

## 📈 Results & Key Findings

### Overall performance

| Metric | Recorded result |
|---|---:|
| Total marketing spend | ₹4.89M |
| Total leads | 125.74K |
| Total conversions | 10,844 |
| Total revenue | ₹35.18M |
| Overall ROI | 619.40% |

### Funnel volume

| Funnel stage | Count |
|---|---:|
| Impressions | 25,300,319 |
| Clicks | 1,197,289 |
| Leads | 125,740 |
| Conversions | 10,844 |

### Channel performance

| Channel | Revenue | ROI |
|---|---:|---:|
| Email Marketing | ₹16.0M | 1,427.56% |
| Google Ads | ₹7.4M | 544.33% |
| Meta Ads | ₹4.9M | 399.17% |
| Instagram | ₹4.5M | 336.82% |
| Facebook | ₹2.4M | 248.95% |

Email Marketing recorded the highest revenue and ROI among the channels represented in the dashboard. Google Ads recorded the second-highest channel revenue.

### Selected campaign results

| Campaign | Spend | Leads | Conversions | Revenue | ROI | CAC |
|---|---:|---:|---:|---:|---:|---:|
| Festive Offers | ₹490,742.39 | 12,225 | 1,028 | ₹3,302,162.83 | 572.89% | ₹477.38 |
| Brand Awareness | ₹403,315.66 | 10,358 | 867 | ₹2,721,412.40 | 574.76% | ₹465.19 |
| New Product Launch | ₹419,172.81 | 10,754 | 901 | ₹2,898,987.47 | 591.60% | ₹465.23 |
| Monsoon Campaign | ₹612,903.65 | 15,714 | 1,363 | ₹4,343,799.41 | 608.72% | ₹449.67 |

*Campaign rows are selected examples from the dashboard, not a complete campaign ranking.*

## 💡 Insights & Business Implications

Based on the recorded dataset and dashboard:

1. **Channel performance differs:** Revenue and ROI vary across the five channels, making channel-level comparisons useful alongside overall results.
2. **Email Marketing stands out in the supplied results:** It records the highest channel revenue and ROI. Further analysis would be needed to understand the strategies and conditions behind this result.
3. **Campaign efficiency varies:** Campaigns show differences in conversions, ROI, and CAC. Reviewing multiple metrics together provides more context than relying on revenue alone.
4. **The funnel narrows substantially:** The dashboard records 125,740 leads and 10,844 conversions. Lead-to-conversion performance is an area to monitor.
5. **Performance changes over time:** Monthly revenue varies across the analysis period and can be used to identify periods for further investigation.

## 💼 Areas for Further Investigation

These are analytical recommendations based on the dashboard—not causal conclusions:

- Review budget allocation using ROI, revenue contribution, and CAC together.
- Investigate the factors associated with Email Marketing's recorded performance before considering whether practices could transfer to other channels.
- Examine channels and campaigns with higher CAC for possible efficiency improvements.
- Analyze lead-to-conversion movement to identify potential lower-funnel opportunities.
- Track monthly results and investigate meaningful changes in campaign performance.
- Establish a recurring dashboard review to support ongoing performance monitoring.

## 🐍 Python Analysis

Python was used for data inspection, validation, KPI recalculation, and exploratory analysis.

**Analysis sequence:** Load dataset → inspect structure → validate and prepare data → calculate KPIs → analyze channels and campaigns → evaluate revenue and ROI.

### Analysis previews

<!-- Add or uncomment these images if the files are present in the repository. -->
<!-- ![Python analysis](Screenshots/python-analysis.png) -->
<!-- ![KPI analysis](Screenshots/kpi-analysis.png) -->

## 📁 Repository Structure

```text
Marketing-Funnel-ROI-Analytics/
├── Dataset/
│   └── Marketing_Funnel_ROI_Analytics_Dataset_1000_Rows.xlsx
├── Python/
│   └── Marketing_Funnel_ROI_Analysis.ipynb
├── PowerBI/
│   └── Marketing_Funnel_ROI_Dashboard.pbix
├── Dashboard/
│   └── Marketing_Funnel_ROI_Dashboard.pdf
├── Documentation/
│   └── Marketing_Funnel_ROI_Analytics_Case_Study.pdf
├── Screenshots/
│   ├── dashboard.png
│   ├── python-analysis.png
│   └── kpi-analysis.png
└── README.md
```

## ⚠️ Limitations

- **Dataset scope:** The analysis uses 1,000 records and may not represent the full complexity of real-world marketing activity.
- **Limited variables:** Customer-level demographics, lifetime value, and detailed audience segments are not included.
- **Attribution:** Multi-touch attribution is not implemented; revenue is analyzed using the available campaign and channel fields.
- **External factors:** Seasonality, competitor activity, market conditions, and changing consumer behavior are not directly incorporated.
- **Causality:** The analysis identifies patterns in the available data but does not establish that marketing activity caused the observed outcomes.

## 🚀 Future Scope

Potential extensions include:

- Customer segmentation and customer lifetime value analysis
- Multi-touch attribution
- Predictive analytics and revenue forecasting
- Campaign performance prediction
- Marketing budget optimization
- Real-time dashboard integration and automated reporting
- More detailed customer-level analysis

These additions could extend the project from descriptive reporting toward predictive and prescriptive analytics.

