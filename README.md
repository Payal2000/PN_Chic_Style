# 📊 UTM Campaign Analytics Dashboard

A complete marketing analytics project that simulates the end-to-end process of analyzing UTM-tagged campaign data—starting from data cleaning and normalization to campaign performance insights, creative effectiveness, lifecycle trends, and keyword intent analysis.



## 🔧 Project Objective

To create a structured, insight-driven Excel-based dashboard that analyzes multi-channel marketing performance using standardized UTM parameters. The project highlights data quality governance, funnel performance, lifecycle tracking, and advanced behavioral segmentation for marketing optimization.


## 📁 Project Phases

### ✅ Phase 1: Data Cleaning & UTM Governance

- Normalized UTM values (e.g., source, medium, campaign) by trimming spaces and converting to lowercase
- Validated numeric fields (clicks, conversions, revenue) for proper formatting
- Handled missing `utm_term` values and dropped incomplete rows
- Removed duplicate records to avoid skewed performance metrics
- Ensured consistent tracking values across campaigns



### 📊 Phase 2: Campaign Performance Analysis

- Created calculated KPIs:
  - **CVR** (Conversion Rate)
  - **RPC** (Revenue per Click)
  - **Revenue per Conversion**
- Built pivot tables to assess:
  - Top-performing campaigns
  - Most efficient traffic sources & mediums
  - Best-performing creatives (e.g., `video_ad` vs `banner1`)
- Applied conditional formatting to highlight high/low performers



### 📈 Phase 3: Funnel & Lifecycle Trends

- Added a **Campaign Start Date** using a `MINIFS()` lookup
- Calculated **Lifecycle Month** using `DATEDIF()`
- Tracked CVR and RPC performance by lifecycle month per campaign
- Used line charts and heatmaps to detect saturation and fatigue trends



### 🧠 Phase 4: Advanced Behavioral Insights

- **Source–Medium Cohorts**: Compared revenue trends over time by source-medium pairs
- **Campaign Lifecycle Trends**: Analyzed campaign ramp-up and drop-off patterns
- **Creative Fatigue**: Tracked CVR/RPC by `utm_content` over months to detect saturation
- **Engagement Funnel Drop-off**: Identified high-click, low-conversion traffic sources
- **Keyword Intent Clustering**:
  - Grouped `utm_term` into `purchase_intent` and `exploratory`
  - Compared each cluster’s performance on clicks, CVR, RPC



## 📌 Final Output

- ✅ Excel workbook with:
  - Cleaned & enriched UTM data
  - Multiple Pivot Table dashboards
  - Custom lifecycle and funnel analysis
  - Heatmaps, line charts, and performance summaries
- ✅ Actionable insights for marketing teams to optimize:
  - Ad spend
  - Creative strategy
  - Landing page experiences
  - Keyword targeting based on intent



## 📎 Tools Used

- Microsoft Excel (Pivot Tables, Power Query, Formulas)
- Conditional Formatting
- Manual tagging + semantic classification (intent_cluster)



## 📍 Author

**Payal Nagaonkar**  
Data Analyst | Marketing Insights | Funnel Optimization  
📫 [LinkedIn](https://www.linkedin.com/in/payal-sanjay/)

---

## 🧩 Sample Metrics

| KPI               | Value         |
|------------------|---------------|
| Total Clicks      | 301,918       |
| Total Conversions | 29,805        |
| Average CVR       | 19.58%        |
| Average RPC       | $3.71         |

---

> 📣 *This project showcases a complete analytics workflow using UTM-tagged data and is a powerful template for real-world marketing analytics in e-commerce, SaaS, and DTC campaigns.*

