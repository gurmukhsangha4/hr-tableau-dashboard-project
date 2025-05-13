# Dynamic HR Analytics Dashboard

> **Interactive Tableau workbook that surfaces workforce trends—headcount, attrition, diversity, and performance—through clear KPIs and drill‑down visuals.**

---

## Project Snapshot

* **Tooling:** Tableau 2024.1 (free Public edition compatible)
* **Data:** Synthetic HR CSV (1,500 rows, 25 columns) generated with Faker + manual tweaks.
* **Visuals:** KPI tiles, donut attrition breakdown, cohort heat‑map, salary box‑plots, and filterable line charts.

![dashboard-preview](assets/hr_dashboard_preview.png)

---

## Quick Start

1. **Clone** the repo and open `hr_analytics.twb` (or `.twbx`) in Tableau Desktop.<br>

   ```bash
   git clone https://github.com/<user>/hr-analytics-dashboard.git
   cd hr-analytics-dashboard
   ```
2. If prompted, **locate the CSV** (`data/hr_dataset.csv`). Tableau auto‑refreshes extracts.
3. Explore with the side filters (Department, Gender, Tenure Band) to see KPIs update in real time.

---

## Folder Layout

```
├── data/                 # raw & cleaned CSVs
├── screenshots/          # preview images for README & repo card
├── hr_analytics.twbx     # packaged Tableau workbook (includes data)
└── README_HR_Analytics_Dashboard.md
```

---

## Key Insights Uncovered

* **Attrition Hotspots:** Sales & Support drove 58 % of annual turnover.
* **Gender Pay Gap:** Median salary gap narrowed from 12 % → 6 % after policy changes in 2023.
* **Tenure vs Performance:** Employees >5 yrs tenure scored 0.4 higher on average performance ratings.

---

## Contributing

PRs that add new metrics (e.g., promotion rate, training hours) or improve design are welcome. Just open an issue first so we can align.

---

## License

MIT – free to fork, tweak, and deploy.
