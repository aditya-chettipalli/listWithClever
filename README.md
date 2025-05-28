# listWithClever

# Housing Market Data Analysis

## Overview

This project involves analyzing housing affordability across U.S. states (including DC and Puerto Rico) using census and Redfin data. The analysis focuses on:

* Total population
* Median household income
* Median sale price of homes
* House affordability ratio (sale price / income)

The final output replicates an Excel spreadsheet and provides additional insights and visualizations.

## Data Sources

* **KEYS.csv**: Metadata file for matching region names and identifiers.
* **CENSUS\_POPULATION\_STATE.tsv**: Contains state-wise population data.
* **CENSUS\_MHI\_STATE.csv**: Includes median household income estimates.
* **REDFIN\_MEDIAN\_SALE\_PRICE.csv**: Lists the most recent monthly median home sale prices.

## Key Processing Steps

1. **Data Cleaning and Mapping**

   * Normalized region names for consistent mapping.
   * Added a custom entry for Puerto Rico in the Redfin dataset, which was missing originally.

2. **Calculated Metrics**

   * Total Population
   * Median Household Income
   * Median Sale Price
   * Affordability Ratio

3. **Ranking and Formatting**

   * Ranked each state for population, income, sale price, and affordability using Excel-style rank suffixes.
   * Constructed descriptive blurbs for each metric.

4. **Output File**

   * Generated a final CSV matching the Excel OUTPUT tab format.

## Visualizations

To complement the analysis, the following visualizations were created:

* **Histogram**: Shows the distribution of median household income across states.
* **Bar Plot**: Highlights the top 10 states by median sale price.
* **Bar Plot**: Illustrates house affordability ratio for each state.
* **Scatter Plot**: Displays correlation between income and sale price.
* **Correlation Heatmap**: Visualizes relationships between income, home price, and affordability ratio.

## Notes

* Normalization of region names ensured accurate mapping between datasets.
* Special handling was implemented for missing or mismatched data entries, particularly for DC and Puerto Rico.

## Dependencies

* pandas
* numpy
* seaborn
* matplotlib

## Output

* `output.csv`: Final cleaned and enriched data file.
* Visual plots are displayed inline in Jupyter Notebook.

## Usage

This project can be run in a Jupyter Notebook environment. Ensure all required data files are correctly placed and paths updated before execution.



