# Startup Market Analysis

Exploratory analysis of startup funding to identify market trends and inform investment evaluation from a pre-2015 perspective.

## Data
Company-level funding records and annual totals of returned funds.
Source: educational datasets provided by Yandex Practicum. Original datasets are not included.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Analysis
- Preprocessed the data: removed duplicates, handled missing values, and checked data types.
- Analyzed funding distributions and the prevalence of different investment types.
- Examined annual trends in average funding round size and the number of rounds.
- Identified mass-market segments and analyzed their funding trends.
- Calculated the ratio of returned funds to funding by funding type and examined changes over time.
- The tables were not merged directly because they have different levels of aggregation. Investment analysis used `cb_investments`, while returned-funds analysis used aggregated data from `cb_returns`. This avoided unnecessary duplication and made the calculations more efficient.

## Key findings
- Technology segments show some of the most notable funding growth. Design has the largest investment volume and the highest funding levels through much of the study period. Software, Internet, and Enterprise Software also show sustained growth.
- Venture capital accounts for the largest investment volume, while seed and angel financing are used at earlier stages of company development.
- The ratio of returned funds to funding is more stable for venture capital, while angel and seed investments show greater volatility.

## Recommendation
Prioritize Software and Internet for further investment evaluation, with a focus on venture capital. Funding activity alone does not establish investment profitability.

## Project file
The Jupyter notebook contains the analysis, visualizations, and conclusions.
