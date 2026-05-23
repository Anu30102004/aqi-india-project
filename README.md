# aqi-india-project
# Air Quality Index Analysis — Indian Cities

## Overview
End-to-end Data Science project analysing AQI across 26 Indian 
cities (2015–2020) using real government pollution data.

## Key Findings
- Ahmedabad had the highest average AQI in the dataset
- Winter AQI is significantly higher than Summer (p < 0.0001)
- CO is the strongest AQI driver (r > 0.85)
- Yesterday's AQI is the best predictor of today's AQI

## Models
| Model              | R²    | RMSE  |
|--------------------|-------|-------|
| Linear Regression  | 0.913 | 28.9  |
| Random Forest      | 0.923 | 38.9  |

## Tools
Python · Pandas · Scikit-learn · Matplotlib · Seaborn · SciPy
