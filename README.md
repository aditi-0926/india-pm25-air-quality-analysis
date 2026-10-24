# India PM2.5 Air Quality Analysis (2019–2025)

## Project Overview

This project analyzes PM2.5 air pollution across Indian cities from 2019 to 2025 using Python, Pandas, and Tableau. It explores geographical pollution patterns, seasonal variations, monthly fluctuations, and long-term trends through an interactive dashboard.

## Objectives

- Analyze PM2.5 concentration patterns across Indian cities and states.
- Identify cities with comparatively high average PM2.5 concentrations.
- Explore monthly and seasonal pollution variations.
- Examine year-wise trends in PM2.5 measurements.
- Present insights through an interactive Tableau dashboard.

## Dataset

- **Records:** 727,887
- **Geographical coverage:** 283 distinct cities across India
- **Time period:** January 2019 – December 2025
- **Primary metric:** PM2.5 concentration, measured in µg/m³

**Data source:** [XKDR Air Quality Database](https://airquality.xkdr.org/)

The dataset contains PM2.5 measurements, observation dates, city and state information, monitoring station details, and geographical coordinates.

**Attribution:** Data sourced from the India Air Quality Database maintained by XKDR Forum, with monitoring data and other sources credited according to the original database documentation.

## Tech Stack

- **Python** – Data processing and analysis
- **Pandas** – Data cleaning and transformation
- **Jupyter Notebook** – Exploratory data analysis
- **Tableau** – Interactive dashboard development
- **GitHub** – Version control and project documentation

## Project Workflow

1. Collected air-quality data from the XKDR Air Quality Database.
2. Cleaned and processed the dataset using Python and Pandas.
3. Prepared city, state, date, and PM2.5 fields for analysis.
4. Explored geographical, monthly, seasonal, and annual pollution patterns.
5. Connected the processed data to Tableau.
6. Designed an interactive dashboard to communicate key findings.

## Dashboard Features

The Tableau dashboard includes:

- **KPI Cards:** Average PM2.5, cities covered, highest city average, stations covered, and peak recorded PM2.5.
- **India Pollution Map:** Geographical distribution of PM2.5 measurements.
- **Top 5 Cities:** Comparison of cities with high average PM2.5 concentrations.
- **Annual Trend:** Year-wise changes in recorded PM2.5 concentrations.
- **Monthly Trend:** Monthly pollution fluctuations.
- **Seasonal Analysis:** Pie chart and heatmap for seasonal comparisons.
- **State-Level Analysis:** Treemap highlighting differences across states.

## Key Analytical Focus

- Identifying geographical differences in recorded PM2.5 concentrations.
- Comparing pollution patterns across cities and states.
- Exploring seasonal and monthly fluctuations.
- Examining changes in recorded measurements across years.

## Limitations

- Data availability varies across some months, particularly in 2025, which may affect comparisons.
- Extremely high or negative PM2.5 readings require additional validation before drawing conclusions.
- Different city-name labels may represent the same or closely related geographical areas.
- PM2.5 concentration is not equivalent to the Air Quality Index (AQI).

Therefore, observed trends should be interpreted in the context of data completeness and measurement quality.

## Future Improvements

- Validate unusual measurements and investigate missing monitoring periods.
- Standardize city and state names.
- Improve temporal comparisons using consistent data coverage.
- Add more detailed city-level and state-level insights.

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from data preprocessing with Python to interactive visualization in Tableau. It provides a geographical and temporal exploration of PM2.5 air pollution across India and showcases practical skills in data preparation, exploratory analysis, and dashboard development.
