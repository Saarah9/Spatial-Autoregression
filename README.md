# Spatial-Autoregression-Simulations
This project explores the bias and efficiency of Ordinary Least Squares (OLS) and First-order Autoregressive (FAR) models in the presence of spatial dependence. Simulations demonstrate the impact of spatial weights and autoregressive parameters on model performance.
## Features
- **Grid-based Spatial Weight Matrix**: A custom 10x10 grid weight matrix to simulate spatial interactions.
- **OLS vs. FAR Models**: Comparison of coefficient estimates, bias, and stability across 100 simulations.
- **Visualization**: Histograms illustrating the distribution of OLS and FAR estimates.
- **Metrics**: Calculations of bias and standard deviation for each method.
## Dependencies
The required Python libraries are:
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- statsmodels
- libpysal
- pysal
## Results
Key Observations:
* OLS: Less biased and more stable, despite ignoring spatial dependence.
* FAR: Shows instability in coefficient estimates due to potential multicollinearity and issues in spatial lag estimation.
