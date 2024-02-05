# Forecasting Japan's Demographic Trends

## Project Overview

This project explores a century of Japan's demographic data (1922-2022) to analyze and forecast trends in birth rates and total births. Utilizing linear regression models, both basic and advanced, this analysis aims to provide insights into Japan's future demographic landscape under current trends.

## Data Sources

- **Birth Rate Dataset**: Contains detailed records of birth rates, including gender ratios, fertility rates, and more, over the last 100 years in Japan.
- **GDP Dataset**: Historical economic data for Japan, used to examine the relationship between economic factors and birth rates.
- The datasets were merged to create a comprehensive analysis base.

## Methodology

1. **Data Preprocessing**: Initial steps involved importing datasets, merging the birth rate and GDP data, and performing necessary cleaning tasks like handling missing values and converting date columns.

2. **Exploratory Data Analysis (EDA)**: Employed visualizations to understand the distribution of various engineered features, including mother's age at firstborn, average family size, and more.

3. **Feature Engineering**: Created several features to deepen the analysis, such as GDP growth rate, legitimacy rate, and gender disparity in births and deaths.

4. **Forecasting Models**:
   - **Basic Linear Regression**: Forecasted the birth rate using GDP, fertility rate, and total population as features.
   - **Advanced Linear Regression**: Extended the model by statistically forecasting GDP, fertility rate, and total population first, then using these forecasts as inputs to predict total births.

## Findings

- Both models predict a continuous decline in birth rates and total births if current trends persist.
- The advanced model, which incorporates forecasts of key socioeconomic indicators, provides a more nuanced view of the future, highlighting the impact of economic and social variables.

## Conclusion

This project underscores the significance of linear regression models in demographic forecasting. By examining Japan's demographic trends through both basic and advanced lenses, it offers a comprehensive view of potential future scenarios shaped by economic performance, fertility trends, and population dynamics.

