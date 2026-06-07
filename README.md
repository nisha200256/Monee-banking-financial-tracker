# Monee Banking Segment — Monthly Financial Performance Tracker

**Built by:** Nisha K G
**Position applied:** Business Finance Analyst — Sea Limited (Monee), Singapore
**Tools used:** Microsoft Excel — Advanced Formulas, Cross-sheet Links, Conditional Formatting, Forecast Modelling, KPI Dashboard

---

## Why I Built This Project

I applied for a Business Finance Analyst role at Sea Limited's Monee banking segment.
To demonstrate my analytical skills and understanding of finance operations,
I independently built this Excel workbook simulating the exact work a finance analyst
would do in the banking segment — month-end reporting, variance analysis,
KPI tracking, forecasting, and management reporting.

---

## Workbook Structure — 5 Sheets

| Sheet | What It Does |
|---|---|
| **Raw Data** | Monthly P&L inputs — Revenue, Operating Costs, Active Users, NPL Rate, Transaction Volume across Indonesia, Philippines, Vietnam for FY2025 (Jan–Dec) |
| **Budget vs Actuals** | Variance analysis comparing actual revenue vs budget. Auto-flags in red when variance exceeds 5%. Green/red conditional formatting for instant visual insight |
| **KPI Dashboard** | 5 KPIs auto-calculated from Raw Data across all 12 months and 3 markets |
| **Forecast Model** | 3-month rolling forecast (Oct–Dec 2025) with adjustable growth rate assumptions. Change one cell — entire model updates |
| **Mgmt Summary** | Executive one-page management report — P&L summary, KPI scorecard, finance commentary, risks, and action items |

---

## 5 KPIs Tracked

| KPI | Formula | Target |
|---|---|---|
| Revenue MoM Growth % | (This Month − Last Month) ÷ Last Month | > 3.0% |
| Cost-to-Income Ratio | Operating Costs ÷ Revenue | < 65% |
| NPL Rate | Non-Performing Loans % | < 3.0% |
| Active User Growth MoM % | (This Month Users − Last Month) ÷ Last Month | Positive |
| Revenue per Active User | Revenue ÷ Active Users | Growing |

---

## Key Excel Features Used

- Cross-sheet formula linking (Raw Data → KPI Dashboard → Mgmt Summary)
- IFERROR formulas for clean error handling
- Conditional formatting with custom color rules (green = positive, red = negative)
- Dynamic forecast model using locked cell references ($B$5)
- Variance flagging formula: =IF(ABS(variance%)>0.05,"FLAG","OK")
- Industry-standard color coding:
  - 🔵 Blue text = hardcoded inputs (you type these)
  - ⚫ Black text = formula-calculated values
  - 🟢 Green text = cross-sheet links
  - 🟡 Yellow background = adjustable assumptions

---

## Markets Covered

| Market | Role in Segment |
|---|---|
| Indonesia | Largest market — ~62% of total revenue |
| Philippines | Mid-tier — strong user growth trajectory |
| Vietnam | Fastest growing — highest MoM revenue growth |

---

## Results From the Model (Sep-25 Snapshot)

| Metric | Indonesia | Philippines | Vietnam |
|---|---|---|---|
| Revenue (SGD '000) | 11,000 | 4,300 | 2,500 |
| Gross Profit (SGD '000) | 4,500 | 1,600 | 850 |
| Gross Margin % | 40.9% | 37.2% | 34.0% |
| Cost-to-Income | 59.1% | 62.8% | 66.0% |
| NPL Rate | 1.9% | 2.3% | 2.7% |

---

## Data Disclaimer

All figures are simulated based on publicly available Southeast Asian fintech
benchmarks. This does not represent actual Sea Limited or Monee financial data.
Built purely for analytical demonstration purposes.

---

## Skills This Project Demonstrates

- Advanced Microsoft Excel
- Financial variance analysis
- KPI design and tracking
- Budgeting and forecasting methodology
- Management reporting format
- Fintech and banking domain understanding
- Southeast Asia market knowledge (Indonesia, Philippines, Vietnam)

---

## Contact

**Email:** nishakg2002@gmail.com
**LinkedIn:** linkedin.com/in/nisha-kg
**GitHub:** github.com/nisha-kg
