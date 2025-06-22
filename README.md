# california-housing-eda-capstone
Exploratory Data Analysis of California Housing Prices using the cleaned dataset. Part of Capstone Two for the Springboard Data Science Career Track. Includes statistical summaries, visual insights, and feature engineering to support future predictive modeling.
This project is part of the Springboard Data Science Career Track and focuses on performing exploratory data analysis (EDA) using a cleaned version of the California housing dataset.

🔍 Project Objective

To analyze the relationships between various features in the California housing dataset and understand what factors influence housing prices across different regions. The ultimate goal is to identify meaningful patterns that can guide feature selection for future modeling.

📁 Files Included

california_housing.csv — Cleaned dataset

02_eda_california_housing.ipynb — Jupyter Notebook with full EDA

eda_summary.md — Written summary of key insights

Visuals folder with:

Boxplots

Correlation heatmap

Scatterplots

Key EDA Steps

Summary statistics and distribution plots

Boxplots to spot outliers

Correlation matrix and heatmap

Scatter plots for top correlated variables

Feature engineering (population_per_household)

Group comparisons by ocean_proximity

Main Takeaways

Median Income has the strongest positive correlation with housing prices.

Some variables like latitude and population also show strong trends with the target variable.

There are clear housing price differences depending on the region's ocean proximity.

Several outliers exist but were retained for now to preserve data variability.
 Next Steps

Use these insights to guide model selection and feature engineering.

Apply regression or ensemble models to predict housing prices.

