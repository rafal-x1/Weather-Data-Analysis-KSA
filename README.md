# Weather Data Analysis (Saudi Arabia, 2022–2025)

## Project Overview
This project analyzes weather data from Saudi Arabia between 2022–2025.  
It includes data cleaning, exploratory data analysis (EDA), and visualizations.

## Steps
1. **Data Loading**: Read weather dataset into pandas DataFrame.  
2. **Data Cleaning**:  
   - Converted `Date` + `Time` → `datetime`.  
   - Extracted `year` and `month`.  
   - Cleaned `Temperature`, `Humidity`, and `Precipitation` columns.  
3. **EDA**: Calculated monthly average temperatures, top weather conditions, humidity distribution.  
4. **Visualizations**: Line chart, bar chart, histogram.

## Results
- **Fair** weather dominates most days (~80%).  
- Clear temperature seasonality (hot summers, cooler winters).  
- Precipitation data was always `0.0` in dataset (likely due to station limitation).  

## Figures
![Temperature Trend](figures/temperature_trend.png)  
![Top Conditions](figures/top10_conditions_bar.png)  
![Humidity Distribution](figures/humidity_hist.png)

---
Made with Python, Pandas, Matplotlib, and Seaborn.
