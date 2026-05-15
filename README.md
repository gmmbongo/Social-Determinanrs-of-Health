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
│   └── clh_2023_county_2_0.xlsx     # AHRQ county-level SDOH dataset
│
├── sdoh_exploration.ipynb           # Main analysis notebook
└── README.md                        # This file
```

## Key Questions

- Which counties have the highest overlap of poverty, uninsured rates, and unemployment?
- Are counties with high poverty farther from hospitals and trauma centers?
- How does broadband access vary by region — and what does that mean for telehealth?
- Which racial groups face the greatest concentration of poverty at the county level?

## Tools & Libraries

- Python 3 · Pandas · NumPy · Jupyter Notebook

## Status

🔄 Module 2 — Data loading, inspection, cleaning, and exploration complete.  
📊 Module 3 — Visualization and correlation analysis coming next.
