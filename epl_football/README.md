# EPL Home Advantage Analysis

## Project Overview
Statistical analysis of 25 English Premier League seasons (2000/01 – 2024/25) across 9,380 matches to determine whether home advantage is real, what drives it, and which popular football myths hold up to scrutiny.

## Key Findings
* Home teams win **45.8%** of matches vs **29.5%** for away teams — a statistically significant gap (p ≈ 0)
* The 2020/21 COVID season (no fans) is the **only season in 25 years** where away wins exceeded home wins
* Away wins being more common in the second half of the season is a **myth** (p = 0.846)
* High-shot-volume teams are **not inefficient** — they win more despite a marginally lower conversion rate
* Home teams receive **fewer cards per foul** than away teams across every foul-count category

## Tools & Techniques
* **Language:** Python 3.x
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, scikit-learn
* **Methods:** Hypothesis testing (z-test, Mann-Whitney U), exploratory data analysis, foul-bin analysis
* **Dataset:** EPL match data — 9,380 matches, 22 features, 25 seasons

## Analytical Impact
* Statistically confirmed home advantage using a z-test (z = 18.7, p ≈ 10⁻⁷⁷)
* Debunked two widely held football myths with p-values
* Identified crowd presence as a likely driver of home advantage using the 2020/21 season as a natural experiment
* Found consistent referee leniency pattern — home teams booked at 13.7% vs 16.1% per foul for away sides

## Files
* `notebook.ipynb` — Full analysis with code and visualisations
* `epl_final.csv` — Match-level EPL dataset (source:  [football-data.co.uk.])

## Author
**Fawaz Durosimi** — Data Analyst
