# Unraveling-the-Sun's-Influence-A-Causal-Analysis-of-Temperature-Anomalies-and-Sunspots

Overview

This project investigates the causal impact of sunspot number (SSN), CO₂ concentration, and volcanic activity on temperature anomalies using statistical modeling, machine learning, and causal inference techniques.

Hypotheses

Sunspot number (SSN) has a significant causal impact on temperature anomalies.

CO₂ concentration has a significant causal impact on temperature anomalies.

Volcanic activity has a significant causal impact on temperature anomalies.

Dataset

The dataset used is final_merged_dataset.csv , after extracting data from multiple sources ( whole process specified in Jupyter notebook) , which includes the following features:

SSN: Sunspot number

CO2: Atmospheric CO₂ concentration

Volcanic Activity: Indicator of volcanic eruptions

Monthly Anomaly: Temperature anomaly values (target variable)


Here’s how I’d summarize the ML models I used in this project:

Linear Regression – I started with a simple linear model to estimate the impact of Sunspot Number (SSN), CO₂ levels, and volcanic activity on temperature anomalies.

XGBoost Regressor – I used this to improve predictive accuracy and analyze feature importance. It performed better than linear regression.

Double Machine Learning (DML) with Random Forest – I applied this for causal inference, estimating the effect of SSN while controlling for CO₂ and volcanic activity.

Double Machine Learning (DML) with XGBoost – I tested XGBoost within the DML framework to compare causal effects using a more powerful model.

Quantum Machine Learning Model (QML) – Finally, I experimented with a quantum model to see if it could speed up computations. While it was a fun test, the results showed that traditional ML models still performed efficiently. But quantum computing is evolving, so it was worth the try!

*Running the Code*

Place final_merged_dataset.csv in the project directory.

Run each script (starting from predictive analysis code block) sequentially in a Jupyter Notebook or Python environment.

Analyze the outputs and visualizations to interpret causal relationships.

Future Work:

Experiment with additional causal models like Instrumental Variables (IV).

Apply non-parametric methods for causal estimation.

Further refine feature selection based on domain knowledge.
