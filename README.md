**Electric Cycle Demand Analysis – Yulu**
**Project Overview**

This project analyzes rental demand patterns for Yulu, a shared electric micro-mobility service provider.

The objective was to identify the key factors influencing electric cycle rentals using statistical analysis and visualization. The insights help improve fleet planning, demand forecasting, and business strategy.

**Problem Statement**

Yulu has observed fluctuations in rental demand and wants to understand:

Does working day status affect rentals?

Do seasons influence demand?

Does weather impact usage?

Are weather and season related?

The goal is to provide data-driven insights to support operational and strategic decisions.

**Dataset Information**

The dataset contains 10,886 records with 12 variables including:

season

holiday

workingday

weather

temp

atemp

humidity

windspeed

casual

registered

count (Target variable)

**Methodology**
1️.) Data Preparation

Imported CSV data using Pandas

Checked data types & converted categorical variables

Verified missing values

Generated statistical summary

2️.) Exploratory Data Analysis (EDA)

Univariate Analysis → Histograms & Countplots

Bivariate Analysis → Boxplots (count vs season, weather, workingday)

3️.) Hypothesis Testing

Two-Sample T-Test → Working vs Non-Working Day

ANOVA → Season vs Count, Weather vs Count

Chi-Square Test → Weather vs Season

4️.) Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

**Key Insights**

Weather significantly impacts rental demand.

Seasonal variation affects usage patterns.

Clear and comfortable temperatures (~15–30°C) show highest rentals.

High humidity and wind reduce usage.

Registered users drive the majority of demand.

No significant difference between weekday and weekend usage.

**Business Recommendations**

Increase fleet availability during high-demand seasons.

Use dynamic pricing based on weather conditions.

Strengthen subscription plans to retain registered users.

Promote weekend leisure rides to grow casual segment.

Use weather-based demand forecasting for smarter operations.

**Limitations**

No demographic or ride-duration data included.

Broad weather categories limit granular analysis.

Assumptions of statistical tests may not fully hold due to skewed distributions.

Future improvements could include predictive modeling and machine learning for demand forecasting.

**Final Takeaway**

Electric cycle demand is strongly influenced by environmental comfort rather than calendar type.

By aligning operations with seasonal and weather patterns, micro-mobility companies can improve utilization, reduce costs, and enhance rider satisfaction.
