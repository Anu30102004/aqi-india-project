# Air Quality Analysis — Indian Cities

This was my final year project for my Data Science degree. I wanted 
to work with something real and relevant to India, so I chose air 
quality data from the CPCB (via Kaggle).

## What surprised me
I went in expecting Delhi to dominate just like every news article does. 
But in this dataset, Ahmedabad came out on top. After digging in, 
it makes sense ; Ahmedabad has a heavy industrial belt and the 
dataset has stronger coverage for Gujarat stations.

CO turned out to be more correlated with AQI than PM2.5 in this 
dataset. I think this reflects how vehicle-heavy Indian cities are 
compared to datasets from other countries where industrial/dust 
sources drive PM2.5 more.

## If I had more time
- I'd add weather data (temperature, wind speed) as features
- Try an LSTM model for proper time series forecasting
- Look at COVID-19's impact on AQI in 2020
