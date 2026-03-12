
# 📊 Global Ads Performance Analytics

> **An end-to-end Excel analytics project analyzing $11.1M in digital ad spend across Google Ads, Meta Ads & TikTok Ads — uncovering budget inefficiencies, seasonal patterns, and data-driven optimization opportunities worth $7M+ in incremental revenue.**

<br>

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data](https://img.shields.io/badge/Records-1%2C800%20Rows-2563EB?style=for-the-badge)
![Platforms](https://img.shields.io/badge/Platforms-Google%20%7C%20Meta%20%7C%20TikTok-FF0050?style=for-the-badge)
![Year](https://img.shields.io/badge/Period-Jan–Dec%202024-0F766E?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-15803D?style=for-the-badge)

<br>

---

## 📌 Table of Contents

- [Problem Statement](#-problem-statement)
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Workbook Structure](#-workbook-structure--10-sheets)
- [Key KPIs](#-key-kpis--full-year-2024)
- [Top Findings](#-top-findings)
- [Tools & Skills Used](#-tools--skills-used)
- [Project Files](#-project-files)
- [How to Use](#-how-to-use)
- [Author](#-author)

---

## 🏢 Problem Statement

> *A digital marketing agency managing **$11.1M in annual ad spend** across three platforms — Google Ads, Meta Ads, and TikTok Ads — has no unified analytical framework to evaluate campaign performance, identify budget inefficiencies, and make data-driven optimization decisions.*
>
> *As a result, budget is being allocated by habit rather than data, causing significant revenue leakage, missed market opportunities, and an inability to justify strategic decisions to clients.*

**This project solves that problem** by building a complete analytics framework — from raw data to interactive dashboard — that answers 17 specific research questions across 5 analytical categories.

---

## 🗺️ Project Overview

```
Raw Data (1,800 rows)
      │
      ▼
Data Cleaning & Standardisation
      │
      ▼
Analytical Framework (5 Categories · 17 Questions)
      │
      ├── Platform Analysis
      ├── Campaign Type Analysis
      ├── Geographic Analysis
      ├── Industry Vertical Analysis
      └── Time & Trend Analysis
            │
            ▼
    Pivot Tables & Cross-Tab Matrices
            │
            ▼
    Interactive Dashboard (4 Slicers · 7 Charts · 9 KPIs)
            │
            ▼
    Insights & Recommendations
```

---

## 📂 Dataset

| Attribute | Detail |
|-----------|--------|
| **Total Records** | 1,800 rows |
| **Time Period** | January 2024 — December 2024 |
| **Platforms** | Google Ads · Meta Ads · TikTok Ads |
| **Campaign Types** | Search · Display · Video · Shopping |
| **Industries** | SaaS · EdTech · Fintech · Healthcare · E-commerce |
| **Countries** | UAE · UK · USA · Germany · Canada · India · Australia |

### 📋 Columns (14 fields)

| Column | | Description |
|--------|------|-------------|
| `date` |  | Campaign date |
| `platform` |  | Ad platform (Google / Meta / TikTok) |
| `campaign_type` |  | Search / Display / Video / Shopping |
| `industry` |  | Target industry vertical |
| `country` |  | Target country |
| `impressions` |  | Total ad impressions |
| `clicks` |  | Total clicks |
| `CTR` |  | Click-through rate (%) |
| `CPC` |  | Cost per click ($) |
| `ad_spend` |  | Total ad spend ($) |
| `conversions` |  | Total conversions |
| `CPA` |  | Cost per acquisition ($) |
| `revenue` |  | Revenue generated ($) |
| `ROAS` |  | Return on ad spend (Revenue ÷ Spend) |

---

## 🗂️ Workbook Structure — 10 Sheets

| # | Sheet | Purpose |
|---|-------|---------|
| 1 | 📋 **Problem Statement** | Defines the business problem this project solves |
| 2 | 📊 **Raw Data** | Original 1,800-row unmodified dataset |
| 3 | ✅ **Cleaned Data** | Standardised, formatted, analysis-ready version |
| 4 | 🗺️ **Factors** | Mind map — 5 categories, 17 research questions |
| 5 | 📅 **Monthly Trends** | Month-by-month KPIs, peak & dip analysis |
| 6 | 📡 **Platform & Campaign** | Platform ROAS comparison + 3×4 Campaign Type ROAS matrix |
| 7 | 🌍 **Country & Industry** | Geographic efficiency + industry vertical performance |
| 8 | 🔀 **Pivot Analysis** | 3 cross-tab pivot tables (Platform×Industry, Country×Platform, Month×Platform) |
| 9 | 📈 **Dashboard** | Interactive dashboard with 4 slicers, 7 charts, 9 KPI cards |
| 10 | 💡 **Insights** | Prioritised recommendations with expected impact |

---

## ⚡ Key KPIs — Full Year 2024

| KPI | Value |
|-----|-------|
| 💰 Total Ad Spend | **$11.11M** |
| 📈 Total Revenue | **$54.18M** |
| 💡 Gross Profit | **$43.07M** |
| ⚡ Blended ROAS | **6.45x** |
| 🎯 Total Conversions | **3,26,812** |
| 👆 Average CTR | **3.84%** |
| 🖱️ Total Clicks | **71.33L** |
| 📊 Total Impressions | **18.53 Cr** |
| 📉 Average CPA | **$46.61** |

---

## 🔍 Top Findings

### 1️⃣ Platform — Budget vs Performance Mismatch

| Platform | ROAS | Spend Share | Revenue Share | Gap |
|----------|------|-------------|---------------|-----|
| Google Ads | 4.11x | 57.2% | 40.7% | **-16.5pp** ⚠️ |
| Meta Ads | 6.92x | 19.0% | 22.0% | +3.0pp ✅ |
| TikTok Ads | **9.54x** | 23.9% | 37.3% | **+13.4pp** 🏆 |

> 💡 **TikTok Ads ROAS (9.54x) is 132% higher than Google Ads (4.11x)** — yet receives only 23.9% of budget vs Google's 57.2%.

---

### 2️⃣ Campaign Type — Platform × Format ROAS Matrix

| Platform | Display | Search | Shopping | Video |
|----------|---------|--------|----------|-------|
| Google Ads | 3.68x | 4.79x | 3.75x | 4.14x |
| Meta Ads | 7.27x | 6.90x | 6.77x | 6.76x |
| **TikTok Ads** | **10.04x** | **10.52x** ⭐ | **8.06x** | **9.57x** |

> ⭐ **Best combination:** TikTok Ads + Search = **10.52x ROAS**
> ❌ **Worst combination:** Google Ads + Display = **3.68x ROAS**

---

### 3️⃣ Geography — Revenue Efficiency by Country

| Country | ROAS | Rev/$ Spent | Spend Share | Efficiency Rank |
|---------|------|------------|-------------|-----------------|
| 🇮🇳 India | 6.65x | **$5.50** | 13.0% | 🥇 #1 |
| 🇦🇺 Australia | 6.67x | $4.99 | 14.3% | #2 |
| 🇩🇪 Germany | 6.71x | $4.96 | 14.0% | #3 |
| 🇦🇪 UAE | **6.96x** | $4.92 | 14.5% | #4 |
| 🇺🇸 USA | 5.81x | $4.16 | **15.6%** | ❌ #7 |

> 💡 **India** delivers the highest revenue efficiency ($5.50 per $1 spent) but receives the **smallest budget allocation** (13%) — the biggest geographic opportunity in the dataset.

---

### 4️⃣ Industry — Performance by Vertical

| Industry | ROAS | Revenue | Profit Margin | CPA |
|----------|------|---------|---------------|-----|
| **SaaS** | 6.65x | **$1,18.92L** | **80.2%** 🏆 | $45.77 |
| EdTech | **6.83x** | $1,15.50L | 80.1% | $48.04 |
| Healthcare | 6.59x | $1,09.31L | 79.3% | $47.56 |
| Fintech | 6.03x ⚠️ | $1,01.73L | 77.7% ⚠️ | $46.59 |
| E-commerce | 6.13x | $96.37L | 80.0% | **$45.04** 🏆 |

> ⚠️ **Fintech** receives the 2nd highest spend but delivers the **lowest ROAS (6.03x) and lowest profit margin (77.7%)** — flagged for immediate audit.

---

### 5️⃣ Seasonality — Monthly Revenue Pattern

```
Revenue ($L)
55 |                    ████                              ████
50 |     ████           ████                              ████
45 |     ████ ████ ████ ████      ████      ████ ████ ████ ████
40 |     ████ ████ ████ ████ ████ ████ ████ ████ ████ ████ ████
35 |     ████ ████ ████ ████ ████ ████ ████ ████ ████ ████ ████
   Jan  Feb  Mar  Apr  MAY  JUN  JUL  Aug  Sep  Oct  Nov  DEC
                            ⚠️Q3 DIP⚠️              ✅ Q4 PEAK ✅
```

| Period | Signal | Action |
|--------|--------|--------|
| **April** | +16.7% MoM revenue | Strong month — maintain spend |
| **May–July** | 🔴 3-month dip — July lowest (21,920 convs) | Counter-cyclical budget strategy |
| **October** | Best ROAS — 7.10x | Front-load Q4 campaigns |
| **December** | Peak month — 7.17x ROAS, 32,282 convs | Maximum budget deployment |

---


## 🛠️ Tools & Skills Used

### Tools
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

### Excel Skills Demonstrated

| Category | Skills |
|----------|--------|
| **Data Cleaning** | Column standardisation, date formatting, number formatting, derived columns |
| **Formulas** | `SUMIF`, `AVERAGEIF`, `AVERAGEIFS`, `SUMPRODUCT`, `IFERROR` |
| **Lookup & Reference** | `INDEX`, `MATCH`, `MAX`, `MIN`, `GETPIVOTDATA` |
| **Date Functions** | `MONTH()`, `TEXT()`, date extraction from datetime stamps |
| **Pivot Tables** | Cross-tab analysis, grouped by month, dynamic slicers |
| **Charts** | Bar charts, pie charts, radar/spider chart, clustered bar |
| **Dashboard** | Interactive slicers (4), KPI cards (9), connected pivot tables |
| **Analysis** | MoM growth %, ROAS matrix, budget vs revenue gap analysis |

---



## 👤 Author

**Pranit**
- 🔗 [GitHub]((https://github.com/pranitlokare))

---


<div align="center">

**⭐ If you found this project useful, please give it a star!**

*Built using Microsoft Excel · Data Analysis · Dashboard Design*

</div>
