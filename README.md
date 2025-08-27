# 3D Print Run Analytics — Power BI Mini Project

**Last updated:** 2025-08-27

This repository is a complete, **plug‑and‑play** Power BI project. Open the PBIX and explore immediately, or preview the PDF in‑browser.

- **▶️ View the report (PDF):** [docs/Report.pdf](docs/Report.pdf)
- **⬇️ Download the PBIX:** [pbix/FactRuns.pbix](pbix/FactRuns.pbix)
- **🎨 Theme:** [theme/powerbi_theme.json](theme/powerbi_theme.json)
- **📂 Data (optional refresh):** [data/](data/) — clean CSV, Excel template, and data dictionary
- **🧮 DAX & Power Query:** [scripts/](scripts/) — measures and M code

## Skills Demonstrated
- Data modeling (star schema, date table, relationships)
- DAX KPIs (on‑time %, reprint %, runtime utilization)
- Time intelligence (MTD/QTD/YTD), context transition
- Visual design for stakeholder consumption (KPI strip + drilldowns)
- Documentation and reproducibility

## How to Use
1. Open **[pbix/FactRuns.pbix](pbix/FactRuns.pbix)** in Power BI Desktop → visuals load with included data.
2. For quick sharing, point people to **[docs/Report.pdf](docs/Report.pdf)**.
3. (Optional) To refresh with local files, update **Transform data → Data source settings** to the files in `./data/` and Refresh.

## Repo Structure
```
.
├─ README.md
├─ pbix/
│  └─ FactRuns.pbix
├─ docs/
│  └─ Report.pdf
├─ data/
│  ├─ 3d_print_runs_clean.csv
│  ├─ 3d_print_data_dictionary.csv
│  └─ BA_portfolio_template.xlsx
├─ scripts/
│  ├─ dax_measures.txt
│  └─ power_query_M.txt
└─ theme/
   └─ powerbi_theme.json
```

## Notes
- If pushing to GitHub, large `.pbix` files should use **Git LFS**.
- Data here is anonymized/sample and suitable for portfolio demonstration.
