# Madrid-District-EDA
Exploratory Data Analysis (EDA) of Madrid's urban zoning and demographics using Python (Pandas &amp; Matplotlib)
# Madrid City Data Analysis: Urban & Demographic Insights

## Project Overview
This project conducts an Exploratory Data Analysis (EDA) of the city of Madrid, focusing on [mention the main topic: e.g., real estate market trends, demographic distribution, or short-term rental density]. The goal was to understand the disparities between different districts and identify patterns that characterize the city's urban structure.

This project was developed as part of the Data Analytics curriculum at **Nuclio Digital School**.

## Business & Analytical Questions
The analysis aims to answer the following questions:
* **Zonal Segmentation:** How does [Main Metric, e.g., rental price] vary between the central "M30" almond and peripheral districts?
* **Distribution Analysis:** Which districts show the highest concentration of [Variable A], and is there a correlation with [Variable B]?
* **Outlier Detection:** Are there specific zones that behave significantly differently from the city average?

## Methodology
The workflow followed a structured data analysis pipeline:

1.  **Data Ingestion & Auditing:** Loaded raw data and performed an initial audit to check for duplicates, missing values, and inconsistent data types.
2.  **Data Cleaning (Trust & Quality):**
    * Handled missing values in [Column Name] by [Strategy: e.g., imputation with median / removal].
    * Standardized district names to ensure consistent grouping.
    * Removed illogical outliers (e.g., negative values or zero-price listings) to ensure analysis integrity.
3.  **Exploratory Analysis (EDA):** Used Pandas for aggregation (groupby) and pivoting to extract summary statistics per district.
4.  **Visualization:** Created static visualizations using Matplotlib to communicate trends effectively.

## Key Insights
* **The "Central Gap":** The data reveals a significant gap of [X]% in [Metric] between the Centro district and the southern districts, highlighting distinct socioeconomic zones.
* **High Density Areas:** [District Name] accounts for [Y]% of the total records, suggesting it is a hotspot for [Activity/Housing].
* **Correlation:** A [positive/negative] correlation was observed between [Variable A] and [Variable B], indicating that as [A] increases, [B] tends to [increase/decrease].

*Note: These insights are based on a static dataset from [Year/Date] and represent a snapshot of the market conditions.*

## Tools & Libraries
* **Python 3.x**
* **Pandas & NumPy:** For data manipulation and vectorization.
* **Matplotlib:** For data visualization.

## Project Structure
* `notebooks/01_data_cleaning.ipynb`: Detailed steps on how raw data was processed.
* `notebooks/02_exploratory_analysis.ipynb`: The main analytical breakdown and visualizations.
