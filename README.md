# Marketing Campaign ROI Analysis

A complete marketing analytics portfolio project that analyzes campaign performance, lead quality, revenue impact, ROAS, ROI, and budget efficiency across multiple marketing channels.

This project demonstrates how marketing data from different platforms can be cleaned, connected, analyzed, and translated into practical business recommendations.

---

## Project Overview

Marketing teams often track impressions, clicks, and leads, but those numbers alone do not show whether a campaign is actually helping the business grow. A campaign may generate many leads, but if those leads do not become qualified leads, customers, or revenue, the business may still be wasting money.

The goal of this project was to answer one main business question:

> Which marketing channels and campaigns are producing quality leads, customers, revenue, and ROI, and where is ad spend being wasted?

To answer this, I created a realistic end-to-end marketing analytics workflow using raw platform-style data exports from advertising, website analytics, email marketing, and CRM sources. The project connects marketing activity with business outcomes so that campaign decisions are based on revenue and lead quality, not only surface-level metrics.

---

## Business Problem

The business was using multiple marketing channels, including Google Ads, Facebook Ads, Instagram Ads, SEO, email marketing, direct traffic, and referral traffic. However, the data was scattered across different sources.

The main problem was that management could see marketing activity, but it was difficult to understand the full journey from campaign spend to actual revenue.

This created questions such as:

- Which channel is bringing the highest-quality leads?
- Which campaigns are generating customers and revenue?
- Which campaigns look good on clicks but perform poorly in sales?
- Where is the business spending too much for weak results?
- How should the marketing budget be improved for better ROI?

---

## What I Did

In this project, I worked through the full marketing analytics process:

1. Collected realistic raw data exports from multiple marketing sources.
2. Cleaned and standardized inconsistent campaign, channel, service, and date formats.
3. Combined marketing performance data with CRM lead and revenue data.
4. Created a cleaned daily performance dataset for analysis.
5. Calculated key marketing KPIs such as CTR, CPC, CPL, cost per qualified lead, ROAS, and ROI.
6. Built channel-level, campaign-level, and service-level performance summaries.
7. Created charts and dashboard visuals to explain performance clearly.
8. Developed business recommendations based on lead quality, customer conversion, revenue, and budget efficiency.

---

## Tools and Skills Used

| Area | Tools / Skills |
|---|---|
| Data Cleaning | Excel, Python, CSV processing |
| Data Analysis | SQL, Python, Excel formulas |
| Dashboarding | Excel dashboard and KPI summaries |
| Marketing Analytics | CTR, CPC, CPL, ROAS, ROI, conversion rate, lead quality |
| Business Analysis | Budget optimization, campaign evaluation, revenue attribution |
| Reporting | Final project report, README documentation, recommendation writing |

---

## Data Sources

This project uses realistic synthetic data created for portfolio demonstration. It does not include confidential or real company data.

| Dataset | Description |
|---|---|
| `meta_ads_raw_export.csv` | Simulated Meta Ads export for Facebook and Instagram campaigns |
| `google_ads_raw_export.csv` | Simulated Google Ads search campaign export |
| `website_traffic_ga4_raw_export.csv` | Simulated GA4-style website traffic export |
| `email_marketing_raw_export.csv` | Simulated email marketing performance export |
| `crm_leads_raw_export.csv` | Simulated CRM leads with qualification status, customer status, and revenue |
| `cleaned_daily_performance.csv` | Final cleaned dataset used for KPI analysis |
| `channel_kpi_summary.csv` | Channel-level performance summary |
| `campaign_kpi_summary.csv` | Campaign-level performance summary |
| `service_kpi_summary.csv` | Service-level performance summary |
| `recommendations.csv` | Final business recommendations based on analysis |

---

## Key KPIs Analyzed

The project focuses on both marketing performance and business performance.

| KPI | Why It Matters |
|---|---|
| Spend | Shows how much budget was used by channel or campaign |
| Impressions | Measures how many times ads or content were shown |
| Clicks | Shows initial audience interest |
| Sessions | Measures website visits from campaigns |
| Leads | Shows how many people submitted interest |
| Qualified Leads | Measures lead quality beyond basic form submissions |
| Customers | Shows how many leads converted into paying customers |
| Revenue | Connects marketing activity to business income |
| CTR | Measures ad or content engagement |
| CPC | Shows cost efficiency of traffic generation |
| Conversion Rate | Shows how well traffic becomes leads |
| Cost per Lead | Measures lead acquisition cost |
| Cost per Qualified Lead | Measures the real cost of useful leads |
| ROAS | Measures revenue generated per dollar spent |
| ROI | Measures overall return after marketing cost |
| Lead Qualification Rate | Shows the quality of leads generated |

---

## Dashboard and Visual Insights

### Revenue by Channel

This chart shows which marketing channels contributed the most revenue.

![Revenue by Channel](assets/revenue_by_channel.png)

### Cost per Qualified Lead by Paid Channel

This chart helps identify where paid marketing spend was efficient and where optimization was needed.

![Cost per Qualified Lead by Paid Channel](assets/cost_per_qualified_lead_by_paid_channel.png)

### Monthly Spend vs Revenue

This chart compares marketing spend and revenue over time to understand monthly performance trends.

![Monthly Spend vs Revenue](assets/monthly_spend_vs_revenue.png)

---

## Main Findings

The analysis showed that not all leads had the same business value. Some channels generated a high number of leads but had weaker lead quality or lower revenue contribution.

### Overall Results

| Metric | Result |
|---|---:|
| Total Marketing Spend | $66,177.04 |
| Total Attributed Revenue | $655,259.11 |
| Total Leads | 5,408 |
| Qualified Leads | 2,090 |
| Customers | 308 |
| Overall ROAS | 9.90x |
| Overall ROI | 890.2% |

### Channel-Level Insights

- **Google Ads** was the strongest paid channel, generating the highest revenue, most qualified leads, and strongest paid ROAS.
- **SEO** created strong long-term value because it generated qualified leads and revenue without direct media spend in the dataset.
- **Facebook Ads** generated useful lead volume, but its cost per qualified lead was higher than Google Ads.
- **Instagram Ads** had the weakest paid performance and needed budget review or campaign optimization.
- **Email Marketing** had low spend and strong efficiency, but lower customer volume compared to major acquisition channels.

---

## Business Recommendations

Based on the analysis, the business should:

1. Increase investment in campaigns that generate qualified leads, customers, revenue, and strong ROAS.
2. Reduce or optimize campaigns with high cost per qualified lead and weak revenue performance.
3. Evaluate campaigns using qualified leads and customers instead of only clicks or total leads.
4. Improve landing pages for campaigns with high traffic but low conversion rates.
5. Continue investing in SEO and email marketing because they support lower-cost long-term lead generation.
6. Review campaign performance with the sales team so marketing and sales agree on what counts as a quality lead.

---

## Project Files

```text
marketing_campaign_roi_project/
├── assets/
│   ├── revenue_by_channel.png
│   ├── cost_per_qualified_lead_by_paid_channel.png
│   └── monthly_spend_vs_revenue.png
├── data/
│   ├── raw/
│   │   ├── meta_ads_raw_export.csv
│   │   ├── google_ads_raw_export.csv
│   │   ├── website_traffic_ga4_raw_export.csv
│   │   ├── email_marketing_raw_export.csv
│   │   └── crm_leads_raw_export.csv
│   └── cleaned/
│       ├── cleaned_daily_performance.csv
│       ├── channel_kpi_summary.csv
│       ├── campaign_kpi_summary.csv
│       ├── service_kpi_summary.csv
│       └── recommendations.csv
├── docs/
│   ├── Marketing_Campaign_ROI_Final_Project_Report.docx
│   ├── Marketing_Campaign_ROI_Final_Project_Report.md
│   └── Marketing_Campaign_ROI_Project_Report_and_Explanation.docx
├── notebooks/
│   └── marketing_campaign_roi_analysis.ipynb
├── sql/
│   └── schema_and_analysis_queries.sql
├── Marketing_Campaign_ROI_Analysis_Workbook.xlsx
├── START_HERE.md
└── README.md
```

---

## Excel Workbook Structure

The Excel workbook includes the following sheets:

- `Start_Here`
- `Data_Dictionary`
- `Raw_Meta`
- `Raw_Google`
- `Raw_Website`
- `Raw_Email`
- `Raw_CRM`
- `Cleaned_Daily`
- `Channel_KPIs`
- `Campaign_KPIs`
- `Service_KPIs`
- `Lead_Quality`
- `Recommendations`
- `Dashboard`
- `QA_Checks`

The workbook is designed to show the complete process from raw data to dashboard-ready insights.

---

## SQL Analysis

The SQL file includes database structure and analysis queries for answering business questions such as:

- Which channels generated the most revenue?
- Which campaigns had the highest ROAS?
- Which campaigns had the highest cost per qualified lead?
- Which services generated the most customers?
- Which marketing activities should be scaled, optimized, or reduced?

---

## Python Analysis

The Python notebook supports the analysis by:

- Loading cleaned marketing datasets
- Calculating KPI summaries
- Creating channel and campaign-level analysis
- Generating visual charts
- Supporting recommendation logic

---

## How to Use This Project

1. Open `START_HERE.md` for a simple explanation of the project.
2. Open `Marketing_Campaign_ROI_Analysis_Workbook.xlsx` and start with the `Dashboard` sheet.
3. Review `Channel_KPIs`, `Campaign_KPIs`, and `Lead_Quality` for detailed analysis.
4. Check `sql/schema_and_analysis_queries.sql` to see the business analysis queries.
5. Open `notebooks/marketing_campaign_roi_analysis.ipynb` to review the Python workflow.
6. Read the final report inside the `docs/` folder for the full business explanation.

---

## Portfolio Value

This project demonstrates my ability to work with marketing data in a business-focused way. It shows that I can move beyond reporting basic campaign numbers and connect marketing performance with lead quality, customers, revenue, and budget decisions.

The strongest value of this project is that it turns scattered marketing data into clear business direction. It shows how data can help a company reduce wasted ad spend, improve campaign performance, and make smarter marketing decisions.

---

## Interview Explanation

I created a marketing campaign ROI analysis project using realistic synthetic data from Meta Ads, Google Ads, GA4-style website analytics, email marketing, and CRM leads. I cleaned and combined the data, calculated KPIs such as CTR, CPC, cost per lead, cost per qualified lead, ROAS, and ROI, and analyzed which channels generated leads, qualified leads, customers, and revenue. The final recommendations focused on shifting budget toward high-performing campaigns and reducing spend where lead quality and revenue performance were weak.

---

## Data Disclaimer

This project uses realistic synthetic data for learning and portfolio purposes. The dataset was created to represent real-world marketing analytics situations, but it does not include confidential, private, or real company data.
