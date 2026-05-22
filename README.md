# sdoh-health-equity-analysis

Exploring the social and economic factors that drive health outcomes across U.S. counties using the AHRQ Community Level Health (CLH) dataset.

## About the Project

This project analyzes 2023 county-level data on poverty, food insecurity, housing costs, broadband access, transportation, uninsured rates, and distance to healthcare facilities — to understand which communities face the greatest health risks and why.

The analysis connects to priorities at major healthcare organizations like Humana and UnitedHealth, which actively use SDOH data to identify high-risk members and reduce preventable costs.

## Dataset

- **Source:** [AHRQ Community Level Health Data](https://www.ahrq.gov/data/innovations/clh-data.html)
- **File:** clh_2023_county_2_0.xlsx
- **Coverage:** 3,234 U.S. counties · 669 variables · 2023
- **Key topics:** Poverty, insurance, food access, housing burden, broadband, transit, healthcare distance, racial disparities

## Project Structure

```
sdoh-health-equity-analysis/
│
├── data/
│   └── sdoh_county_2023.csv           # Cleaned SDOH county dataset (32 key variables)
│
├── charts/                            # All exported chart images
│
├── sdoh_exploration.ipynb             # Week 1: Load, inspect, clean, explore
├── sdoh_week2_eda.ipynb               # Week 2: EDA, groupby, first draft visuals
├── sdoh_week4_visualizations.ipynb    # Week 4: Polished, ethical visualizations
└── README.md

```

## Key Questions

- Which counties have the highest overlap of poverty, uninsured rates, and unemployment?
- Are counties with high poverty farther from hospitals and trauma centers?
- How does broadband access vary by region — and what does that mean for telehealth?
- Which racial groups face the greatest concentration of poverty at the county level?

## Key Findings So Far

- The **South** leads on all four hardship indicators — poverty, uninsured, unemployment, and lack of broadband
- **Poverty and uninsured rates** are strongly correlated (r = 0.70+) at the county level
- **Racial poverty gaps** are structural and national — Black poverty rates are the highest in every Census region
- The **broadband-poverty gap** creates a telehealth access crisis in the counties that need it most
- Over **400 counties** score in the high vulnerability range across all 5 hardship indicators

## Tools & Libraries

- Python 3 · Pandas · NumPy · Matplotlib · Jupyter Notebook

## Progress

| Week | Notebook | Focus |
|---|---|---|
| Week 1 | sdoh_exploration.ipynb | Load, inspect, clean, basic wrangling |
| Week 2 | sdoh_week2_eda.ipynb | EDA, groupby, first draft visuals |
| Week 4 | sdoh_week4_visualizations.ipynb | Polished charts, ethics reflection, story direction |
| Week 5+ | Coming soon | Narrative, final presentation |
