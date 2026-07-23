# Portfolio Guide

A summary of my data analyst projects and case studies — SQL analysis, Power BI dashboards, and the recommendations behind each finding.

---

## SQL & Power BI Projects

| Project | Tools | Description | Key Finding |
|---|---|---|---|
| 🩺 [NY State Asthma ED Visits Analysis](#) | SQL Server, Power BI | Two-page dashboard analyzing 3,870 real emergency department visit records from the NY State Department of Health (2000–2019) — an overview page (statewide trend, most-improved counties, top counties by ED visit rate) and a "Who Is Most Affected" page (seasonal patterns, age group, gender). | Real government dataset — statewide ED visit rate dropped from a peak of 101.23 (per 10,000) to 67.01 by the most recent year. The Bronx has by far the highest burden of any county (1,021 per 10,000 — roughly double the next-highest county); ages 0–4 show the highest visit rate (676 per 10,000) of any age group. |
| 🫁 [Synthetic Asthma Patient Analysis](#) | SQL Server, Power BI | Patient-level analysis of 10,000 synthetic clinical records examining prevalence, risk factors, and what actually drives asthma control. | Medication non-adherence is the single strongest differentiator of asthma control — 96.5% of patients have inadequate control, and adherence rises step by step with control level (0.31 → 0.68 → 0.88). |
| 💰 [SaaS Sales Performance Analysis](#) | SQL Server, Power BI | Analysis of 9,994 B2B SaaS transactions (2020–2023, 48 countries, 14 products, 3 segments) examining revenue, profit, and discounting strategy. | Discounting is pushing the best-selling product (ContactMatcher) into negative margins — discounted transactions are net loss-making overall (−$34.5K), while full-price transactions carry the entire business's profit (+$321K). |

---

## Data Engineering / Pipeline Projects

| Project | Tools | Description | Key Finding |
|---|---|---|---|
| 🌦️ [Climate Risk Assessment for Planting — BHF, Kwali](#) | Open-Meteo API, Power Query, SQL Server, Power BI | End-to-end pipeline (API ingestion → transformation → SQL Server storage) plus analysis of 11 years of daily weather data to identify the safest planting window for an agroforestry site. | June–September is the safest planting window (drought risk under 5.2%); November–April carries the highest risk (January: 96.8% drought-risk days). Both drought and heat stress risk have increased meaningfully over the past decade. |

---

⬅️ [Back to my profile](https://github.com/alukuabdullah/alukuabdullah/blob/main/README.md)
