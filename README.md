# 👗 Fashion Market & Sales Analysis — Power BI Dashboard
An interactive 5-page Power BI dashboard analyzing marketing campaign performance and sales outcomes across a Vietnamese fashion retail portfolio. The dashboard integrates marketing spend and sales data to evaluate ROI, surface underperforming campaigns, and support budget-reallocation decisions.

📌 Dataset sourced from a Vietnamese fashion retail market. Some field labels appear in Vietnamese — all KPIs and findings are documented in English.


# 🧩 The Business Problem
Marketing teams often measure campaigns by impressions and clicks — not by whether they actually drove revenue. This dashboard was built to answer three sharper questions:

Which campaigns are actually driving revenue and profit?
Where is marketing budget being wasted?
How should spend be reallocated to improve overall ROI?


# 📊 Dashboard Structure (5 Pages)
PagePurposeGeneral OverviewTop-level KPIs — total revenue, ROAS, budget utilization, top 5 campaigns by spend and ROASrcm - General OverviewRecommendation layer: translates high-level findings into specific reallocation decisionsCampaign AnalysisMarketing funnel, campaign details table, CPM vs CPC vs CP/KQ breakdown by campaignrcm - Campaign AnalysisRecommendation layer: flags underperforming campaigns and surfaces optimization actionsProduct InsightTop 10 products by revenue, SKU-level ROAS ratings, total revenue by city and category

💡 Each analysis page is paired with a dedicated Recommendations view that translates findings into specific budget and campaign decisions — not just data, but action.

# 🔢 Key Numbers
Total Revenue: 3.02B
Total Marketing Spend: 394.13M
Overall ROAS: 7.67
Budget Utilization: 82.75%
Avg CPM: 102K
Avg CTR: 0.88%
Campaigns Analyzed: 25+
SKUs Tracked: 120+

# 🔑 Key KPIs Tracked

Revenue — total and by campaign, market, and SKU
ROAS — return on ad spend per campaign
Budget Utilization % — actual spend vs allocated budget
Avg CPM / CPC / CP/KQ — cost efficiency metrics per campaign
Campaign Contribution % — each campaign's share of total revenue
SKU Rating — product-level performance scoring


#💡 Key Findings

Top-performing campaigns contributed 30–35% of total revenue
Several campaigns had budget utilization exceeding 100% (e.g. Gina Set ib-Op at 104%), signaling overspend without proportional returns
Multiple campaigns operated at ROAS well below the portfolio average of 7.67, indicating budget being consumed without equivalent revenue
Percy Set and Lisa Dress 5 were the top two revenue-generating SKUs — significantly outperforming the rest of the top 10
An estimated ~20% of marketing budget could be reclaimed by reallocating spend away from underperforming campaigns


✅ Recommendations Delivered

Cut or cap campaigns running over budget with below-average ROAS
Double down on top 30–35% revenue-driving campaigns — they have proven conversion efficiency
Establish ROAS thresholds as a minimum bar for campaign approval going forward
Prioritize Percy Set and Lisa Dress 5 in future campaign planning — highest SKU-level revenue contribution
Monitor budget utilization weekly to catch overspend before it compounds


# 🛠 Methodology
A Design Thinking approach was used to frame the entire analysis around the needs of marketing and sales decision-makers — starting from their questions, not the data.

Marketing spend was linked directly to downstream sales outcomes so campaigns could be judged on financial impact, not engagement metrics alone
DAX measures built for revenue, ROAS, budget utilization %, CPM, CPC, and campaign contribution
Each analysis page paired with a dedicated recommendations page — translating numbers into decisions
Visuals structured for drill-down navigation: market → campaign → SKU level
Marketing funnel view tracks drop-off from impressions → clicks → conversions → orders

# 🚀 How to Open

Install Power BI Desktop (free)
Download fashion-market-sales-analysis.pbix
Open in Power BI Desktop
Use the page tabs at the bottom to navigate all 5 views

# ⚠️ Status & Limitations
Version: v1 — learning project, actively iterating
AreaStatusVisual polishLayout and formatting to be refined in v2Data scopeFixed dataset — live refresh not configuredMap visualsRequire tenant-level Power BI settings to renderValidationKPI logic spot-checked, not yet peer-reviewed

# 🗺 Planned Improvements

 Add drill-through pages for individual campaign deep-dives
 Build a forecast view for projected ROAS under different budget-allocation scenarios
 Standardize color palette and font hierarchy across all pages
 Resolve map visual tenant permissions for geographic revenue view
 Add conditional formatting to KPI cards for at-a-glance performance status


# 👤 Author
Khoa (David) Tran
Data Analyst | Power BI · SQL · Python · Tableau
LinkedIn · GitHub
