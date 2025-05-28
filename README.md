# listWithClever

# Housing Market Data Analysis

This project analyzes US state-level housing market data using datasets from Zillow, Redfin, and the US Census Bureau. It cleans, processes, ranks, and visualizes key housing metrics like population, income, sale price, and affordability.

## Data Sources

* **KEYS.csv**: Region mappings and state info
* **CENSUS\_POPULATION\_STATE.tsv**: State-level population estimates
* **CENSUS\_MHI\_STATE.csv**: Median household income data
* **REDFIN\_MEDIAN\_SALE\_PRICE.csv**: Redfin median home sale prices by state

## Features

* Computes metrics for each state:

  * Total population and population rank
  * Median household income and rank
  * Median home sale price and rank
  * Home affordability ratio and rank
* Generates readable descriptions ("blurbs") for each metric
* Saves clean output to a CSV file (`output.csv`)
* Produces visualizations using Seaborn:

  * Distribution of Median Household Income
  * Top 10 states by median sale price
  * Bar plot of house affordability ratio
  * Scatter plot of median household income vs. median sale price
  * Correlation Heatmap of Income, Sale Price, and Affordability

## Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn

## Visualizations

* **Histogram**: Shows the distribution of median household income across states.
* **Top 10 States by Median Sale Price**: Bar chart highlighting the ten states with the highest median home sale prices.
* **Bar Plot of House Affordability Ratio**: Visualizes how affordable housing is across states by comparing home prices to median household income.
* **Scatter Plot of Median Household Income vs. Median Sale Price**: Illustrates the relationship between income and home price, identifying trends and outliers.
* **Correlation Heatmap**: Displays the relationship between income, home price, and affordability, helping identify strong or weak correlations between metrics.

## Usage

Place the CSV files in your local directory and run the notebook. The output will be saved as output.csv and visualizations will display in the notebook itself.


> **Note**: Puerto Rico was not originally included in the Redfin median sale price dataset. A row was manually added to ensure consistent representation across all metrics and states.

## Author

Aditya Chettipalli


