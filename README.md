
# Auckland Cycling Forecast

This project analyzes and forecasts daily cycling counts in Auckland using time series models and weather data. The workflow demonstrates data cleaning, exploratory analysis, seasonality decomposition, forecasting with Prophet, and the impact of holidays and weather on cycling activity.

## Folder Structure

```
auckland-cycling-forecast/
├── classwork.ipynb         # Main analysis notebook
├── cycling_counts_by_day.csv  # Daily cycling counts dataset
├── Auckland_weather_combined.csv # Weather data for Auckland
├── README.md
├── requirements.txt
├── .gitignore
```

## Environment Setup

```bash
# Clone the repository
$ git clone https://github.com/LanreAdetola/auckland-cycling-forecast.git
$ cd auckland-cycling-forecast

# (Optional) Create and activate a virtual environment
$ python3 -m venv venv
$ source venv/bin/activate

# Install dependencies
$ pip install -r requirements.txt
```

## Workflow Outline

1. **Data Loading & Cleaning**
	- Load cycling counts and weather data CSVs
	- Parse dates, handle missing values
2. **Exploratory Data Analysis**
	- Visualize trends, seasonality, and distributions
3. **Time Series Decomposition**
	- Analyze trend, seasonality, and residuals
4. **Forecasting with Prophet**
	- Train Prophet model on historical data
	- Add holiday and custom effects
	- Incorporate weather regressors
5. **Evaluation**
	- Compare predictions to actuals
	- Calculate MAE, RMSE, MAPE
6. **Visualization**
	- Plot forecasts, components, and evaluation results

## Main Files & Datasets
- `classwork.ipynb`: Jupyter notebook with all analysis steps
- `cycling_counts_by_day.csv`: Daily cycling counts
- `Auckland_weather_combined.csv`: Weather features for Auckland

## Tools & Libraries
- Python 3.8+
- pandas
- matplotlib
- seaborn
- numpy
- prophet
- statsmodels
- scikit-learn

## Credits
- Auckland Transport for cycling data
- NIWA for weather data
- Prophet library by Facebook

