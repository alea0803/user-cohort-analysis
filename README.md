# User Retention and LTV Analysis

This project demonstrates how to analyze user behavior through cohort-based metrics such as Retention Rate, Conversion Rate, Lifetime Value (LTV), and ROI using Python and Jupyter Notebook.

## Notebook

The full cohort analysis notebook can be found here:  
[📓 cohort_analysis.ipynb](./cohort_analysis.ipynb)

##  Project Goals

- Evaluate the performance of traffic channels and user cohorts.
- Identify high-performing segments by country, device, and acquisition source.
- Build reusable functions for retention, conversion, and LTV analysis.

##  Stack

- Python (Pandas, Numpy, Matplotlib)
- Jupyter Notebook
- CSV data files (visits, orders, ad costs)

## Key Metrics Implemented

- `get_profiles()` — builds user profiles based on first session
- `get_retention()` — calculates user retention by cohort and day
- `get_conversion()` — calculates conversion rates across cohorts
- `get_ltv()` — computes Lifetime Value over time
- `get_roi()` — calculates ROI using aggregated revenue and ad costs

##  Why this matters

This analysis helps identify how different channels and user segments behave over time. The project can be reused and extended for growth analytics, product retention studies, and marketing efficiency evaluation.

##  Structure

- `notebook.ipynb` — main notebook with analysis and visualizations
- `README.md` — this file
- (Optional) `/data` — sample datasets for demonstration (not included here)

##  Contact

Feel free to reach out if you’d like to discuss this approach or suggest improvements.
