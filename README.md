# Predicting Bank Default Risk in Ukraine (2009-2025)

## Project Overview
This project aims to identify early warning indicators of bank liquidations and insolvencies using Machine Learning. The analysis is built on 16 years of raw, unstructured financial statements extracted directly from the National Bank of Ukraine (NBU).

## Tech Stack & Skills
* **Languages:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Seaborn
* **Techniques:** ETL Pipeline, Data Wrangling, Out-of-Time Validation, Feature Engineering

## Key Business Value
Standard ML projects use pre-cleaned datasets. This project focuses on real-world data wrangling and financial analysis:
1. **Custom ETL:** Extracted and aggregated financial metrics across 16 years of changing NBU reporting formats.
2. **Financial Feature Engineering:** Calculated core banking health indicators (ROA, ROE, Liquidity Ratio, Reserves/Loans Ratio) from raw assets and liabilities.
3. **Out-of-Time Validation:** The model is trained on historic systemic crises (2009-2019) and tested on unseen, volatile periods (2020-2024, including COVID-19 and wartime economy) to simulate real-world stress-testing.

## Future Enhancements (Next Steps)
To address "Concept Drift" caused by the 2022 macroeconomic shocks, the model's accuracy could be further improved by integrating external macroeconomic factors directly into the feature set (e.g., NBU Key Rate, UAH/USD volatility, and inflation indices).
