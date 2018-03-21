# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Working with Time Series Data

> Unit 4, Flex

---

## Materials We Provide

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Time Series - I. Working With Time Series Data | [Here](./01_time_series.ipynb) |
| Lesson | Time Series - II. Rolling Statistics | [Here](./02_rolling_statistics.ipynb) |
| Lesson | Time Series - III. Autocorrelation | [Here](./03_autocorrelation.ipynb) |
| Lesson | Time Series - IV. Decomposition | [Here](./04_decomposition.ipynb) |
| Lesson | Time Series - V. Bonus Lesson--Time Series Forecasting Models | [Here](./04_decomposition.ipynb) |
| Coding Exercise  | Independent Exercise | [Here](./05_independent_practice.ipynb) |
| Solution  | Solution Code - I. Time Series Data Applications | [Here](./solution-code/01_time_series_solutions.ipynb) |
| Solution  | Solution Code - II. Rolling Statistics Applications | [Here](./solution-code/02_rolling_statistics_solutions.ipynb) |
| Solution  | Solution Code - III. Autocorrelation Applications | [Here](./03_autocorrelation_solutions.ipynb) |
| Solution  | Solution Code - IV. Decomposition Applications | [Here](./04_decomposition_solutions.ipynb) |
| Solution  | Solution Code - Independent | [Here](./05_independent_practice_solutions.ipynb) |
| Datasets | Apple Stock | [Here](./data/aapl.csv) |
| Datasets | Airline Passengers | [Here](./data/airline.csv) |
| Datasets | Oregon Bus Passengers | [Here](./data/bus.csv) |
| Datasets | European Retail | [Here](./data/euretail.csv) |
| Datasets | Google Stock | [Here](./data/googl.csv) |
| Datasets | Drone Racing | [Here](./data/gt_drone_racing.csv) |
| Datasets | Mapquest Google Trends | [Here](./data/mapquest_google_trends.csv) |
| Datasets | Rossmann | [Here](./data/rossmann.csv) |
| Datasets | Unemployment | [Here](./data/unemployment.csv) |

---

## Learning Objectives

After this lessons, students will be able to:

1. Explain how time series data are distinct and how to account for that.
2. Create rolling means and plot time series data.
3. Perform autocorrelation on sample time series data.
4. Decompose time series data into trend and residual components.
5. Bonus: Explain the benefits and drawbacks of ARIMA as compared to other methods.

---

## Student Requirements

Before this lesson(s), students should already be able to:

1. Manipulate data with Pandas.
2. Create basic data visualizations with Matplotlib and Seaborn.
3. Define and demonstrate techniques for correlating data points.

---

## Lesson Outline

> TOTAL (190 min)
I. **Foundations** (190 min)
* Part 1: Time Series Data (20 min)
    * What is Time Series Data?
    * Examples of Time Series Data and Domains That Find it Useful
    * Trends and Seasonality
    * Preprocessing Time Series Data With Pandas
    * Processing Date Information as datetime Objects
    * Filtering by Date With Pandas
    * Differencing/Lagging
* Practice (15 min)
* Part 2: Rolling Means and Plotting Time Series Data (20 min)
    * What is a Trend?
    * Visualizing Trends
    * Computing Aggregates With Pandas' .resample() Function
    * Computing Rolling Averages With Pandas
    * Other Pandas Window Functions (Rolling Sum, Rolling Max, Diff)
    * Exponentially Weighted Windows
    * Plotting Time Series Data
* Practice (15 min)
* Part 3: Autocorrelation on Time Series Data (25 min)
    * Define Autocorrelation
    * Examples of Autocorrelation
    * Computing Autocorrelation
    * Using the Pandas autocorr() Function
Calculating and Plotting ACF and PACF Using StatsModels
* Practice (15 min)
* Part 4: Decomposing Time Series (15 min)
    * Decomposing Time Series Into Trend, Seasonality, Cyclical, and Residual Components
    * Using the .seasonal_decompose() Function
    * Plotting the Seasonal, Trend, and Residual Components of a Time Series
* Practice (15 min)
* Closing and Recap (5 min)
II. Bonus (30 min)
* Time Series Forecasting Models (25 min)
    * What are Time Series Models?
    * Properties of Time Series Models
    * Assumption of Stationarity
    * Compare/Contrast Time Series Forecasting Models
* Closing and Recap (5 min)

---


## Additional Resources

If you are interested in more resources, check out the following:
* In Pandas' datetime library, search for more information on .dt [here](http://pandas.pydata.org/pandas-docs/stable/api.html).
* For additional review of these concepts, see some inspiration from the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html).
* There are lots of additional tutorials on ARIMA models out there; here is a [good one](http://www.statsref.com/HTML/index.html?arima.html).
