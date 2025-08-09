# Database & Analytics Case Studies

A curated set of **SQL**, **Python**, and **Power BI** projects demonstrating practical data analysis and modeling. Clean structure, reproducible notebooks, and clear write-ups.

## Projects (Spotlight)
| # | Project | What it shows | Tech | Links |
|---|---|---|---|---|
| 1 | SQL Case Studies | Joins, CTEs, window functions, KPIs | SQL | `sql/` |
| 2 | Python ML Case Studies | EDA → feature engineering → baseline ML | Python, scikit-learn, matplotlib | `notebooks/` (`python-case-studies`) |
| 3 | Power BI Dashboards | Interactive business dashboards & metrics | Power BI | `powerbi/` |
| 4 | Data Visualization & EDA | Clean plots, profiling, insights | Python, matplotlib/plotly | `eda/`, `notebooks/` |

> Each folder includes a **mini README** (problem → data → approach → results → how to run).

## Repo Layout
```
notebooks/                  # Jupyter notebooks (one per project)
src/                        # Reusable python modules (utils, pipelines)
sql/                        # SQL scripts / case studies
powerbi/                    # .pbix files + screenshots
data/                       # (empty) include README on how to fetch
reports/                    # PDFs/images of results, dashboards
eda/                        # EDA notebooks
README.md
requirements.txt
.gitignore
LICENSE
```

## Environment
```
python -m venv .venv
source ./.venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Reproducibility
- Notebooks use relative paths (e.g., `data/...`).
- Data is not tracked in git; see `data/README.md` for fetch steps.
- Random seeds set for ML where appropriate.

## License
MIT
