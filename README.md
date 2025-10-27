# COVID-19 Time Series Forecasting

Simple project for analyzing COVID-19 trends and forecasting using Prophet.

## Overview
- Downloads and analyzes COVID-19 data from Our World in Data (OWID).
- Visualizes infection trends.
- Performs short-term forecasting using Prophet.
- Includes decomposition, rolling averages, and graphs.

## Quick Start (Colab)
1. Open `notebooks/COVID19_TimeSeries_Forecasting.ipynb` in Google Colab.
2. Run the cells step-by-step.
3. Change the `COUNTRY` variable at the top to analyze different countries.

## Local Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/COVID19_TimeSeries_Forecasting.ipynb
```

## Data
- The main dataset used: `data/owid-covid-data.csv`
- You can download it from https://www.kaggle.com/datasets/bolkonsky/covid19?resource=download

## Author
**Aradhya Parashar** — 2025
