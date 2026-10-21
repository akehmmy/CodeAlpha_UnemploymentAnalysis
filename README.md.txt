# CodeAlpha_UnemploymentAnalysis

**Data Science Internship — Task 2: Unemployment Analysis with Python**

## Overview
This project analyzes monthly unemployment data for Indian states (May 2019 to Oct 2020) to explore trends, measure the impact of Covid-19, and draw insights that could inform economic and social policy.

## Workflow
1. **Load & inspect** two datasets: a May 2019 to Jun 2020 file with a rural/urban split, and a Jan to Oct 2020 file with regional groupings
2. **Clean**: remove blank rows, standardize column names, convert dates, fix swapped latitude/longitude labels
3. **Explore**: distribution of unemployment rates, monthly national trend
4. **Covid-19 impact**: before / during / after the lockdown, hardest-hit states, regional comparison, jobs lost
5. **Rural vs urban** comparison of unemployment, employment and labour participation
6. **Labour participation** and why the unemployment rate alone can mislead
7. **Patterns**: seasonality (and its limits) and chronic vs shock unemployment
8. **Insights & policy implications**

## Key Findings
- The average state unemployment rate rose from 9.8% before the lockdown to 22.8% in April and May 2020, then returned to about 9.6% by June to October.
- Estimated employment fell about 30% in one month (392.5 to 274.8 million) and had largely recovered by October.
- Puducherry, Jharkhand, Tamil Nadu and Bihar were hit hardest; the East and South were the hardest-hit regions.
- Urban areas were hit harder (+16.0 points vs +13.3 for rural) and recovered more slowly.
- Labour participation in October was still 3.2 points below January, even though the unemployment rate looked recovered.
- A state's pre-lockdown unemployment did not predict how hard the lockdown hit it.

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn

## How to Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Unemployment_Analysis.ipynb
```

## Datasets
- `Unemployment in India.csv`: monthly, May 2019 to Jun 2020, by state and area (rural/urban)
- `Unemployment_Rate_upto_11_2020.csv`: monthly, Jan to Oct 2020, by state with regional grouping

Both provided by CodeAlpha.

## Author
Akor Emmanuel — CodeAlpha Data Science Intern (Student ID: CA/DF1/305488)