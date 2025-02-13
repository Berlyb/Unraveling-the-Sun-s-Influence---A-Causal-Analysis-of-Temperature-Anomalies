# Unraveling-the-Sun's-Influence-A-Causal-Analysis-of-Temperature-Anomalies-and-Sunspots

# Overview

This project investigates the causal impact of sunspot number (SSN), CO₂ concentration, and volcanic activity on temperature anomalies using statistical modeling, machine learning, and causal inference techniques.

## Hypotheses

- Sunspot number (SSN) has a significant causal impact on temperature anomalies.
- CO₂ concentration has a significant causal impact on temperature anomalies.
- Volcanic activity has a significant causal impact on temperature anomalies.

## Dataset

The dataset used is *final_merged_dataset.csv*, which includes the following features:

- **SSN**: Sunspot number
- **CO2**: Atmospheric CO₂ concentration
- **Volcanic Activity**: Indicator of volcanic eruptions
- **Monthly Anomaly**: Temperature anomaly values (target variable)

## ML Models Used

- **Linear Regression**: I started with a simple linear model to estimate the impact of SSN, CO₂ levels, and volcanic activity on temperature anomalies.
- **XGBoost Regressor**: I used this to improve predictive accuracy and analyze feature importance. It performed better than linear regression.
- **Double Machine Learning (DML) with Random Forest**: I applied this for causal inference, estimating the effect of SSN while controlling for CO₂ and volcanic activity.
- **Double Machine Learning (DML) with XGBoost**: I tested XGBoost within the DML framework to compare causal effects using a more powerful model.
- **Quantum Machine Learning Model (QML)**: Finally, I experimented with a quantum model to see if it could speed up computations. While it was a fun test, traditional ML models still performed efficiently. Quantum computing is evolving, so it was worth the try!

## Running the Code

1. Place *final_merged_dataset.csv* in the project directory.
2. Run each script (starting from the predictive analysis code block) sequentially in a Jupyter Notebook or Python environment.
3. Analyze the outputs and visualizations to interpret causal relationships.

## Future Work

- Experiment with additional causal models like Instrumental Variables (IV).
- Apply non-parametric methods for causal estimation.
- Further refine feature selection based on domain knowledge.
