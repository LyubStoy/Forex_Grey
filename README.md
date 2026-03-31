# Forex War Tool – EUR/USD Analysis

## Objective
This project aims to explain and model EUR/USD exchange rate movements using macroeconomic drivers, with a primary focus on yield differentials.

## Structure

- PART I – Economic logic
- PART II – Mathematical modeling
- DataSets – Historical data (EUR/USD, yields, etc.)

## Methodology

- First differences (Δ)
- Pearson correlation
- Regression analysis
- Rolling correlation
- Regime segmentation

## Key Hypothesis

EUR/USD ≈ f(US yields − EU yields)


## Libraries Used

- pandas → data manipulation
- numpy → numerical computations
- matplotlib → data visualization
- scipy → statistical analysis
- statsmodels → econometric modeling (regression, diagnostics)

## Key Modules Used

- matplotlib.pyplot → plotting
- matplotlib.dates → time series formatting
- scipy.stats → Pearson correlation and p-values
- statsmodels.api → regression modeling

## Data sources

    https://fred.stlouisfed.org/series/PAYEMS
    https://fred.stlouisfed.org/series/UNRATE
    https://ec.europa.eu/eurostat/databrowser/view/une_rt_m/default/table?lang=en
    https://www.backtestmarket.com/
    https://widgets.dukascopy.com/en/
    https://www.macrotrends.net/3029/2-year-treasury-yield
    https://data.forexsb.com/
    https://www.tradingview.com/
    https://ca.investing.com/analysis/understanding-the-relationship-between-bond-yields-and-currencies-200474487
    https://treasuryone.co.za/yields-differentials-vs-currency-and-outlook/


## Author
Lyubomir Stoychev
