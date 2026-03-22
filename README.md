# Yulu Bike - Demand Analysis (Hypothesis Testing)

## Overview

Analyzed Yulu bike-sharing data to understand factors affecting demand, identify key drivers of rentals, and generate actionable business insights using statistical analysis and hypothesis testing.


## Dataset

The dataset includes variables such as:

* Datetime (date & time of rental)
* Season, Weather
* Holiday, Working Day
* Temperature, Feels-like Temperature
* Humidity, Windspeed
* Casual, Registered, Count (total rentals)


## Objective

* Understand factors influencing bike rental demand
* Analyze impact of weather, season, and working days
* Perform statistical hypothesis testing
* Derive business insights for demand optimization


## Key Analysis

* Exploratory Data Analysis (EDA)
* Univariate & Bivariate Analysis
* Correlation Analysis (Heatmap)
* Hypothesis Testing:
* T-Test (Working Day vs Demand)
* ANOVA (Season & Weather vs Demand)
* Chi-Square Test (Weather vs Season)
* Assumption Testing (Shapiro-Wilk, Levene’s Test)


## Key Insights

* Weather and season significantly impact bike rentals, with higher demand during favorable conditions.
* Working day does not have a significant effect, indicating usage beyond commuting purposes.
* Temperature positively influences demand up to an optimal range.
* Humidity negatively impacts rentals, reducing user comfort.
* Windspeed shows minimal effect on demand.
* Strong dependency observed between weather and season.


## Model Interpretation (Business Understanding)

### Significant Variables

- The analysis identified the following key variables influencing bike rental demand:

* Weather and season (strong impact)
* Temperature (positive relationship)
* Humidity (negative relationship)

Working day was found to have no statistically significant effect on demand.


### The selected variables describe demand patterns effectively:

* Weather and season show strong variation in rentals.
* Temperature and humidity contribute to understanding user behavior.
* Windspeed and working day have limited influence.

- While the analysis provides strong insights into demand drivers, further modeling (e.g., regression) can quantify the exact contribution of each variable.


## Customer Behavior Insights

* Users prefer riding in comfortable weather conditions.
* Demand peaks during moderate temperatures and clear weather.
* Bike usage is influenced by lifestyle and convenience, not just work commute.


## Tools Used

* Python (Pandas, NumPy, SciPy)
* Matplotlib, Seaborn
* Statistical Testing Methods


## Business Impact

* Enables data-driven demand forecasting
* Supports dynamic bike allocation strategies
* Helps design weather-based pricing models
* Improves operational efficiency and user experience with seasonal and weather patterns, micro-mobility companies can improve utilization, reduce costs, and enhance rider satisfaction.
