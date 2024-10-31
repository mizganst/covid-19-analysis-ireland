Overview
This project analyzes COVID-19 trends in Ireland, focusing on cases and deaths. It uses time-series visualizations, regression models, and hypothetical scenarios to examine the data. The dataset was sourced from the Ireland COVID-19 hub.

Project Breakdown
Data Visualization

Trends: Time series plots display case and death trends, with a 7-day rolling average to smooth short-term fluctuations.
Gender Comparison: Visualizations show any disparities in COVID-19 impact across genders.
Regression Modeling

A linear regression model predicts COVID-19 deaths based on case numbers, with data transformation using log scaling (np.log(X)) to manage skewness and stabilize variance.
Hypothetical Scenarios

Testing Simulation: Predicts case numbers assuming extensive testing from the pandemic's start.
Vaccine Efficacy: Analyzes potential death rates had vaccines been ineffective against the Omicron variant.
Technology
Libraries: pandas, matplotlib, numpy
