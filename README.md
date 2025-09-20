# Probabilistic EBITDA Forecasting

## Business Impact: Improved EBITDA predictability, enabling confident financial planning.

### Project Overview
This project develops a advanced forecasting system that moves beyond single-point estimates to probabilistic EBITDA forecasts with confidence intervals. By modeling underlying business drivers and using Monte Carlo simulation, it provides leadership with a complete view of potential financial outcomes.

### The S.T.A.R.

- **Situation**: EBITDA was highly volatile and difficult to forecast due to complex interactions between pricing, rebates, and cost fluctuations across the product portfolio.
- **Task**: Develop a predictive model to accurately forecast EBITDA by capturing the underlying drivers of margin volatility.
- **Action**:
  - Feature-engineered data on price, cost, units, and customer segments
  - Built time-series models (ARIMA) for key business drivers
  - Performed Monte Carlo simulations to model uncertainty
  - Generated scenario-based forecasts (best/worst case)
- **Result**: Improved EBITDA predictability by 12%, giving leadership confidence in financial planning and the ability to proactively model pricing strategies.

### Key Features
- **Driver-Based Forecasting**: Models underlying business drivers (price, volume, cost) rather than just historical EBITDA
- **Probabilistic Output**: Provides confidence intervals and scenario analysis
- **Monte Carlo Simulation**: Runs 10,000+ simulations to quantify uncertainty
- **Executive Visualizations**: Clear charts showing forecast ranges and risks

### How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Run the Jupyter notebook: `ebitda_forecasting.ipynb`
3. The notebook will generate all forecasts and visualizations

### Technologies Used
- Python (pandas, numpy)
- Statistical Modeling (ARIMA, Linear Regression)
- Monte Carlo Simulation
- Data Visualization (matplotlib, seaborn, plotly)
