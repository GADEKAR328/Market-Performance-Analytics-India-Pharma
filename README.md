<div align="center">

# 📊 Market Performance Analytics — India Pharma

### *Advanced Business Intelligence for the Indian Pharmaceutical Sector*

<br/>

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![DAX](https://img.shields.io/badge/DAX-15%20Formulas-0D2137?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Dataset](https://img.shields.io/badge/Dataset-1200%20Rows%20·%2039%20Cols-0A7C6E?style=for-the-badge)](/)
[![Currency](https://img.shields.io/badge/Currency-INR%20₹-D4A017?style=for-the-badge)](/)
[![FY](https://img.shields.io/badge/Period-FY2022--23%20→%20FY2024--25-8B5CF6?style=for-the-badge)](/)
[![India](https://img.shields.io/badge/Made%20in-Maharashtra%20🇮🇳-FF9933?style=for-the-badge)](/)

<br/>

> 💡 *A portfolio-ready, single-page Power BI dashboard performing advanced market performance analysis on India's pharmaceutical sector — covering revenue trends, regional breakdowns, competitive market share, cost structure analysis, and clinical KPIs across FY2022-23 to FY2024-25.*

</div>

---

## 📸 Dashboard Preview

<div align="center">

![Dashboard Preview](https://raw.githubusercontent.com/GADEKAR328/Market-Performance-Analytics-India-Pharma/a10b1a64afcf45a6635d15a06cd87d066a0e0d07/Market%20Performance%20Analytics%20%E2%80%94%20India%20Pharma.jpg)

</div>

---

## ⚡ Key KPIs at a Glance

<div align="center">

| 💰 Total Revenue | 📈 Net Profit | 📊 Gross Margin | 💊 Units Sold | 🏥 Patients | 🚀 YoY Growth |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **₹ 6.28 Bn** | **₹ 2.13 Bn** | **64.84%** | **480K** | **5M** | **42.69%** |

| 🎯 Avg NPS Score | 💹 Net Margin % | 🏆 Avg Market Share |
|:---:|:---:|:---:|
| **52.62** | **33.88%** | **15.43%** |

</div>

---

## 🗂️ Repository Structure

```
📦 Market-Performance-Analytics-India-Pharma
 ┣ 📊 Market Performance Analytics — India Pharma.pbix    ← Power BI file
 ┣ 🖼️  Market Performance Analytics — India Pharma.jpg    ← Dashboard screenshot
 ┣ 📄 market_performance_india.csv                        ← Dataset (1200 rows · 39 cols)
 ┣ 📋 DAX_Formulas_Market_YSG.pdf                        ← All 15 DAX formulas
 ┗ 📝 README.md                                          ← You are here
```

---

## 📊 Dashboard Visuals

```
┌──────────────────────────────────────────────────────────────────────────┐
│  🏠  Market Performance Analytics — India Pharma    NPS | Margin | Share │
│       YOGESH GADEKAR    [Financial_Year ▼] [Therapy_Area ▼] [State ▼]  │
├──────────┬──────────┬──────────┬──────────┬──────────┬──────────────────┤
│ 💰 6.28B │ 📈 2.13B │ 📊 64.84%│ 💊 480K  │ 🏥 5M    │    🚀 42.69%    │
│  Revenue │  Profit  │  Margin  │  Units   │ Patients │    YoY Growth    │
├──────────────────┬───────────────────┬────────────┬───────────────────┤
│  Bar Chart       │  Bar Chart (H)     │  Donut     │  Clustered Bar   │
│  Revenue Trend   │  Revenue by State  │  By Therapy│  By Channel      │
│  by FY           │                    │  Area      │  Large/Mid Cap   │
├──────────────────┴───────────────────┴────────────┴───────────────────┤
│  Stacked Bar Chart                 │  Matrix Visual                    │
│  Cost Structure                    │  Company × Therapy — Market Share │
│  COGS · Mktg · RnD · Reg · Profit  │  (Color scale heatmap)           │
└────────────────────────────────────┴──────────────────────────────────┘
```

| # | Visual | Description |
|---|--------|-------------|
| 🃏 | **9 KPI Cards** | Total Revenue, Net Profit, Gross Margin %, Units Sold, Patients, YoY Growth %, NPS Score, Net Margin %, Avg Market Share % |
| 📊 | **Bar Chart** | Revenue Trend by Financial Year (FY2022-23 → FY2024-25) |
| 📊 | **Horizontal Bar** | Revenue by State — Maharashtra leads |
| 🍩 | **Donut Chart** | Revenue by Therapy Area — Immunology, Oncology, Neurology breakdown |
| 📊 | **Clustered Bar** | Revenue by Sales Channel — Large Cap vs Mid Cap split |
| 📊 | **Stacked Bar** | Cost Structure — COGS, Marketing, R&D, Regulatory, Net Profit |
| 🔢 | **Matrix Visual** | Company × Therapy Area — Market Share % heatmap |
| 🔽 | **3 Slicers** | Financial_Year · Therapy_Area · State — all dropdown style |
| 🏠 | **Home Bookmark** | Resets all slicers and filters to default state in one click |

---

## ✨ Special Features

### 🏠 Home Bookmark (Reset Button)
A **home icon button** is placed on the dashboard that uses Power BI Bookmarks to reset all slicers and filters back to "All" in a single click — no manual clearing needed.

**How it was built:**
1. Set all slicers to "All" (default state)
2. View → Bookmarks → Add Bookmark → named `Home`
3. Insert → Buttons → Blank → Action = Bookmark → select `Home`
4. Formatted button with a 🏠 home icon

---

## 🧪 Dataset Details

> 📁 File: `market_performance_india.csv` &nbsp;|&nbsp; 🗓️ FY2022-23 to FY2024-25 &nbsp;|&nbsp; 💹 Currency: INR (₹)

**1,200 rows · 39 columns** based on real India pharma market structure

### Companies (10)
| Company | Segment | HQ |
|---------|---------|-----|
| Sun Pharma | Large Cap | Mumbai |
| Cipla | Large Cap | Mumbai |
| Dr. Reddy's Lab | Large Cap | Hyderabad |
| Lupin | Large Cap | Mumbai |
| Aurobindo Pharma | Large Cap | Hyderabad |
| Biocon | Mid Cap | Bengaluru |
| Torrent Pharma | Mid Cap | Ahmedabad |
| Alkem Labs | Mid Cap | Mumbai |
| Abbott India | Large Cap | Mumbai |
| Pfizer India | Large Cap | Mumbai |

### Products & Therapy Areas
| Therapy Area | Example Products |
|---|---|
| Oncology | Trastuzumab 440mg, Imatinib 400mg, Doxorubicin 50mg |
| Diabetes | Metformin 500mg, Sitagliptin 100mg |
| Cardiology | Atorvastatin 20mg, Sacubitril+Valsartan |
| Neurology | Levetiracetam 500mg, Natalizumab 300mg |
| Immunology | Adalimumab 40mg, Secukinumab 150mg |
| Respiratory | Tiotropium 18mcg, Montelukast 10mg |
| Anti-Infectives | Azithromycin 500mg, Meropenem 1g |
| Dermatology | Tacrolimus 0.1% |
| Gastroenterology | Pantoprazole 40mg |
| Pain Management | Etoricoxib 90mg |

### Key Columns
| Column | Type | Description |
|--------|------|-------------|
| `Financial_Year` | Text | FY2022-23, FY2023-24, FY2024-25 |
| `India_FY_Quarter` | Text | Q1–Q4 per India FY (Apr–Mar) |
| `Company_Name` | Text | 10 real pharma companies |
| `Therapy_Area` | Text | 10 therapy segments |
| `State` | Text | 12 Indian states |
| `City_Tier` | Text | Tier 1 / Tier 2 / Tier 3 |
| `Sales_Channel` | Text | Hospital / Retail / Govt / Online / Export |
| `Gross_Revenue_INR` | Decimal | Revenue in ₹ |
| `Net_Profit_INR` | Decimal | Profit after all costs |
| `Market_Share_Pct` | Decimal | Company % share in therapy area |
| `NPS_Score` | Decimal | Net Promoter Score (0–100) |
| `Recall_Risk` | Text | Low / Medium / High |

---

## 🧮 DAX Formulas — All 15

> ℹ️ CC = Calculated Column (right-click table → New Column) &nbsp;|&nbsp; M = Measure (Home → New Measure)

### ⚙️ Calculated Columns

```dax
-- CC-1: Revenue Band
Revenue Band =
SWITCH(TRUE(),
  [Gross_Revenue_INR] >= 5000000, "High",
  [Gross_Revenue_INR] >= 1000000, "Mid", "Low")
```

```dax
-- CC-2: Profit Flag
Profit Flag =
IF([Net_Profit_INR] > 0, "Profitable", "Loss")
```

```dax
-- CC-3: Specialty Flag
Specialty Flag =
IF([Therapy_Is_Specialty] = TRUE(), "Specialty", "General")
```

```dax
-- CC-4: FY Sort Key (use Sort by Column for correct FY axis order)
FY Sort Key =
SWITCH([Financial_Year],
  "FY2022-23", 1, "FY2023-24", 2, "FY2024-25", 3, 99)
```

```dax
-- CC-5: Discount Band
Discount Band =
SWITCH(TRUE(),
  [Trade_Discount_Pct] >= 0.20, "High (>20%)",
  [Trade_Discount_Pct] >= 0.12, "Medium", "Low (<12%)")
```

### 📐 Measures

```dax
-- M-01: Total Revenue
Total Revenue =
SUM(market_performance_india[Gross_Revenue_INR])
```

```dax
-- M-02: Total Net Profit
Total Net Profit =
SUM(market_performance_india[Net_Profit_INR])
```

```dax
-- M-03: Gross Margin %
Gross Margin % =
DIVIDE(
  SUM(market_performance_india[Gross_Profit_INR]),
  SUM(market_performance_india[Gross_Revenue_INR]), 0
) * 100
```

```dax
-- M-04: Net Margin %
Net Margin % =
DIVIDE(
  SUM(market_performance_india[Net_Profit_INR]),
  SUM(market_performance_india[Gross_Revenue_INR]), 0
) * 100
```

```dax
-- M-05: Total Units Sold
Total Units Sold =
SUM(market_performance_india[Units_Sold])
```

```dax
-- M-06: YoY Revenue Growth %
YoY Revenue Growth % =
VAR CY = SUM(market_performance_india[Gross_Revenue_INR])
VAR PY = CALCULATE(
  SUM(market_performance_india[Gross_Revenue_INR]),
  DATEADD(market_performance_india[Txn_Date], -1, YEAR)
)
RETURN DIVIDE(CY - PY, PY, BLANK()) * 100
```

```dax
-- M-07: Avg Market Share %
Avg Market Share % =
AVERAGE(market_performance_india[Market_Share_Pct])
```

```dax
-- M-08: Revenue by Therapy %
Revenue by Therapy % =
DIVIDE(
  SUM(market_performance_india[Gross_Revenue_INR]),
  CALCULATE(
    SUM(market_performance_india[Gross_Revenue_INR]),
    ALL(market_performance_india[Therapy_Area])
  ), 0
) * 100
```

```dax
-- M-09: Total Patients Reached
Total Patients Reached =
SUM(market_performance_india[Patient_Count])
```

```dax
-- M-10: Avg NPS Score
Avg NPS Score =
AVERAGE(market_performance_india[NPS_Score])
```

---

## 🚀 How to Run This Project

```bash
# Step 1 — Clone the repository
git clone https://github.com/GADEKAR328/Market-Performance-Analytics-India-Pharma.git
```

```
Step 2 — Open Power BI Desktop
         Download free → https://powerbi.microsoft.com/desktop
```

```
Step 3 — Load the dataset
         Home → Get Data → Excel Workbook (or Text/CSV)
         Select → market_performance_india.csv
         Table name: market_performance_india
```

```
Step 4 — Add Calculated Columns
         Right-click table in Fields pane → New Column
         Paste CC-1 to CC-5 one by one
```

```
Step 5 — Add Measures
         Home → New Measure
         Paste M-01 to M-10 one by one
         All measures show with ⚡ calculator icon
```

```
Step 6 — Fix Financial_Year sort order
         Select Financial_Year column
         Column Tools → Sort by Column → FY Sort Key
```

```
Step 7 — Add Home Bookmark (Reset Button)
         Set all slicers to "All"
         View → Bookmarks → Add → name it "Home"
         Insert → Buttons → Blank → Action → Bookmark → Home
         Add home icon image on the button
```

```
Step 8 — Open .pbix directly (if uploaded)
```

---

## 🎨 Color Theme

<div align="center">

| Role | Hex | Used In |
|------|-----|---------|
| Primary Navy | `#0D2137` | Header, cards, text |
| Teal Accent | `#0A7C6E` | Chart bars, highlights |
| Gold | `#D4A017` | KPI delta indicators |
| Light Teal | `#E8F5F3` | Card backgrounds |
| Page BG | `#F5F7FA` | Canvas background |
| Red Accent | `#C0392B` | Loss / negative values |

</div>

---

## 📈 Market Insights from Dashboard

- **Maharashtra leads** all states with ₹0.67 Bn revenue — highest pharma market in India
- **Immunology is fastest growing** therapy at 34.56% revenue share — driven by biosimilars
- **Large Cap dominates** all sales channels vs Mid Cap across Hospital, Retail, and Online
- **NPS of 52.62** indicates good customer satisfaction — above industry average of 45
- **YoY Growth of 42.69%** reflects strong post-pandemic recovery in India pharma
- **Net Margin of 33.88%** is above the healthy benchmark of 15–22% for Indian pharma

---

## 🛠️ Tech Stack

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-15%20Formulas-0D2137?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Data%20Generation-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github)

</div>

---

## 👤 About the Author

<div align="center">

### YOGESH GADEKAR (YSG)

📍 Maharashtra, India &nbsp;|&nbsp; 📊 Data Analytics &nbsp;|&nbsp; 💡 Power BI Developer &nbsp;|&nbsp; 🏥 Healthcare Domain

[![GitHub](https://img.shields.io/badge/GitHub-GADEKAR328-181717?style=for-the-badge&logo=github)](https://github.com/GADEKAR328)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D2137&height=100&section=footer" width="100%"/>

### ⭐ Star this repo if you found it useful!

*Built with ❤️ from Maharashtra, India*

</div>
