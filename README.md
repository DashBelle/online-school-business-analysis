# online-school-business-analysis
📊 Business Analysis of an Online Programming School

Business and CRM data analysis project aimed at identifying growth opportunities and improving the operational efficiency of an online programming school.


📌 Project Overview

This project is a full-cycle business analysis based on CRM data from an online school offering courses in Digital Marketing, UX/UI Design, and Web Development.

The analysis covers the entire funnel — from lead generation and marketing campaign performance to sales team efficiency, product profitability, and unit economics — culminating in actionable business recommendations backed by statistical hypothesis testing.


🎯 Business Goals


Identify which marketing channels generate the highest quality leads
Evaluate sales team performance and conversion rates
Assess product profitability by course type and schedule
Calculate unit economics (CPA, CAC, AOV, LTV, CLTV, CM)
Test hypotheses to validate growth strategies



🔍 Analysis Stages

StageDescription1. Data CleaningRemoved duplicates, filled missing values, converted data types2. Descriptive StatisticsCalculated means, medians for numerical fields; analyzed categorical variables3. Data AnalysisTime series of deals and calls, deal closure duration, campaign and channel performance4. Product AnalyticsUnit economics by product, metrics tree, hypothesis formulation and testing


📈 Key Findings

Marketing Channels


Facebook Ads and Google Ads show the highest correlation between spend and revenue
TikTok Ads, CRM, Partnership, and Offline channels have notably low conversion rates, suggesting poor lead quality
Webinar channel delivers the highest conversion rate (6.9%) despite relatively low lead volume


Sales Dynamics


Deal and call volumes peak in March 2024, confirming a strong correlation between call activity and deal closures
The majority of deals close within the first 10 days of creation, indicating a highly efficient sales process


Top Advertising Campaigns


performancemax_digitalmark1_ru_DE leads by total deal volume (2,652 deals)
02.07.23wide_DE achieves the highest conversion rate among top-10 campaigns (5.3%)


Payment Types


Recurring Payments show the highest conversion rate: 71.2% (247 out of 347 deals)
Reservation is the least effective: only 20.0% conversion


Sales Team


Oliver Taylor significantly outperforms peers with a ~30% conversion rate
Kevin Parker and Ulysses Adams follow with ~7% conversion rates


Products


Digital Marketing (Morning) generates 54.8% of total revenue
UX/UI Design (Morning) contributes 25.8%
Evening courses show higher C1 conversion rates, indicating scaling potential



🧪 Hypothesis Testing

Hypothesis 1 — Increase AOV


Offering additional products (books, certificates) at checkout will increase Average Order Value by 10%
Result: H₀ rejected (p-value = 3.39e-99) ✅ Hypothesis confirmed


Hypothesis 2 — Reduce CAC


Optimizing ad campaigns through audience segmentation and personalization will reduce Customer Acquisition Cost by 15%
Result: H₀ rejected (p-value = 2.04e-194) ✅ Hypothesis confirmed



💡 Business Recommendations


Increase AOV — introduce upsell offers (books, certificates) at checkout; expected +10% AOV
Reduce CAC — focus ad spend on segmented, personalized audiences; expected -15% CAC
Optimize marketing mix — prioritize Facebook Ads, Google Ads, and Webinar channels; reduce investment in low-converting channels
Scale evening courses — Digital Marketing and UX/UI Design evening formats show high C1 conversion, suggesting strong scaling potential
Improve sales team performance — replicate Oliver Taylor's practices across the team; improve CRM data quality for better lead management



🛠️ Tech Stack

ToolPurposePythonData processing and analysispandasData manipulation and cleaningmatplotlib / seabornData visualizationscipyStatistical hypothesis testing (t-test)Jupyter NotebookAnalysis environment


📂 Dataset


Source: CRM data from an online programming school (training dataset, IT Career Hub)
Volume: 10,000+ records covering deals, calls, campaigns, payments, and products
Period: June 2023 — June 2024



👩‍💻 Author

Irina Zasenko — Data Analyst
LinkedIn · GitHub

Final project, IT Career Hub Data Analytics Program, September 2025
