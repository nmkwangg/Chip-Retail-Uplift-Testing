# Chip-Retail-Uplift-Testing
Chip Retail Uplift Testing & Experimentation

📌 Project Overview

This project evaluates the impact of a retail trial intervention on chip sales using uplift testing and controlled experimentation.
The goal is to determine whether trial stores experienced a statistically meaningful improvement compared to matched control stores, and to translate those findings into actionable business recommendations.

This analysis mirrors a real-world retail analytics workflow:
data preparation → control selection → trial evaluation → uplift measurement → recommendation.

🧠 Key Questions

- Did the trial stores outperform comparable control stores?

- Is the observed uplift statistically significant?

- Which stores benefited from the trial, and which did not?

- Should the intervention be rolled out, modified, or discontinued?

📊 Data Description

The project uses transactional and customer behavior data from a grocery retail context.

Main datasets

- QVI_data.csv – aggregated sales and transaction metrics (large file, tracked with Git LFS)

- QVI_transaction_data.xlsx – detailed transaction-level data

- QVI_purchase_behaviour.csv – customer purchasing behavior and segmentation data

⚠️ Large files are tracked using Git LFS.
If cloning this repository, ensure Git LFS is installed.

🔬 Methodology

1. Exploratory Data Analysis (EDA)

- Examined data structure, time coverage, and variable distributions

- Identified missing values, anomalies, and data quality issues

- Explored sales trends, seasonality, and customer segment behavior

- Informed downstream feature engineering and control-store selection

2. Data Cleaning & Feature Engineering

- Date normalization and temporal aggregation

- Construction of sales, volume, and transaction-level metrics

- Creation of customer segmentation and behavioral features

3. Control Store Selection

- Identification of suitable control stores based on historical similarity

- Visual and quantitative validation of pre-trial alignment

4. Trial vs Control Comparison

- Pre-trial vs trial-period performance analysis

- Time-series comparisons of key performance indicators

5. Uplift Measurement

- Estimation of incremental sales and performance uplift

- Store-level evaluation rather than pooled averages

6. Business Interpretation & Recommendation

- Clear recommendation for each trial store

- Practical implications for rollout, refinement, or discontinuation

📈 Key Outputs

-Trial vs control performance visualizations

- Store-level uplift analysis

- Reproducible Jupyter notebooks documenting the full workflow
