## Project Walkthrough 

**Objective**: Analyze Air Quality Index (AQI) patterns across Indian cities using real-world CPCB data, identify pollution hotspots, and derive key insights.

**Data**: `city_day.csv` from Kaggle (CPCB, 2015–2020) – ~29,000 rows, 16 columns.

**Preprocessing**:
- Group-by-City **Median Imputation** for missing pollutant values (robust to outliers)
- Dropped rows with missing AQI
- Feature engineering: Year, Month, Season (Winter/Summer/Monsoon)

**Key Insights from EDA**:
- Ahmedabad has the highest average AQI (due to strong industrial station coverage in dataset)
- CO shows stronger correlation with AQI than PM2.5 (reflects vehicular traffic dominance in India)
- Higher pollution in Winter months

**Visualizations**: Top polluted cities barplot, Correlation heatmap, Time-series trends, Seasonal boxplots

**Modeling**: Simple Linear Regression to predict AQI (evaluated using R² and RMSE)

**Limitations & Future Work**:
- Dataset has station coverage bias
- Future: Add weather data, LSTM time-series forecasting, Streamlit dashboard

---
