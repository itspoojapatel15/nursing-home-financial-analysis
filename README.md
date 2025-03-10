# U.S. Nursing Homes Financial Analysis (2015-2021)

This project analyzes the financial performance, quality indicators, and regulatory penalties of U.S. nursing homes from 2015 to 2021 using multiple CMS datasets. It especially emphasizes the impact of COVID-19 on net income, staffing, and operational metrics across facilities of different sizes.

## Project Overview

- Time Period: 2015-2021
- Scope: U.S. Nursing Homes (Small, Medium, and Large)
- Objective:
  - Evaluate financial performance (e.g., net income)
  - Identify key influential features (e.g., occupancy, ownership, ratings)
  - Visualize penalty trends, staffing, and quality over time
  - Assess COVID-19 impact on revenue

## Features Analyzed

- Ownership Type (For-Profit, Non-Profit, Government)
- Number of Beds (Size Category)
- Overall Rating, Staffing Rating, Health Inspection Rating
- Occupancy Rate
- COVID-19 Period Net Income vs. Pre-COVID Net Income
- Fines and Penalties
- Medicaid/Medicare Payer Mix

## Project Structure

sid3_extracted/
|-- data/                  # Raw and cleaned CMS datasets (2015-2021)
|-- notebooks/             # EDA, regression, visualization notebooks
|-- plots/                 # Generated plots and graphs
|-- final report bana620.docx      # Summary report for BANA 620
`-- readme.md              # This file

## Key Graphs and Insights

### 1. COVID Impact on Net Income by Facility Size
![COVID Impact](https://github.com/siddharthreddy232/NursingHome-FinancialAnalysis/blob/main/1st%20qn%20original%20output.png)
Larger facilities (>100 beds) saw up to 1178% increase in net income during COVID-19.

---

### 2. Mean Net Income Pre-COVID vs COVID
![Net Income Periods](https://github.com/siddharthreddy232/NursingHome-FinancialAnalysis/blob/main/qn%205.png)
Net income rose drastically in 2020-2021 compared to 2015-2019.

---

### 3. Penalties and Fines Over Time
![Penalties and Fines](https://github.com/siddharthreddy232/NursingHome-FinancialAnalysis/blob/main/qn%204%20-%202.png)
Fines dropped to zero during COVID, reflecting policy leniency.

## Conclusion Highlights

- COVID-19 Boost: Net income growth was significant in larger facilities during the pandemic.
- Regulatory Relaxation: Almost no penalties or fines issued in 2020-2021.
- Staffing vs. Quality: Staffing ratings declined, but overall quality ratings remained steady.

## Tools and Libraries

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- CMS Public Datasets
- MS Word (for final report)

## Final Report

- See final report bana620.docx for the complete findings and analysis.

## Maintainer

Pooja Patel is a Data Science Graduate specializing in statistical analysis, predictive modeling, and data visualization. With professional experience in Python, R, and SQL, she focuses on streamlining processes and delivering actionable insights from large datasets.

Contact: patel.pooja81599@gmail.com