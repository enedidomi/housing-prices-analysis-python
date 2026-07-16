# Housing Prices Analysis

An end-to-end housing price analysis project using Python to clean, explore, visualize, and analyze a housing prices dataset.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib

## Project Structure

- **analysis/** – Python notebook containing the complete data analysis, visualizations, correlation analysis, and regression analysis.
- **data_cleaning/** – Python notebook documenting the data cleaning and preprocessing steps.
- **screenshots/** – Images of the visualizations and analysis results.

## Analysis Includes

- Data Cleaning
- Data Exploration
- Descriptive Statistics
- Data Visualization
- Correlation Analysis
- Simple Linear Regression

## Findings

The dataset contains 1,460 houses with an average sale price of $180,921. The average house has 1,515 sq ft of living space, 2.87 bedrooms, 1.57 full bathrooms, and an average overall quality rating of 6.1 out of 10. The houses in the dataset were built between 1872 and 2010, with prices ranging from $34,900 to $755,000.

The distribution of house prices shows that most houses are sold between $100,000 and $200,000, while only a small number of houses are sold at much higher prices. The boxplot also shows the presence of some high-priced outliers.

The scatter plot and regression line show a clear positive relationship between living area and sale price, meaning that larger houses generally sell for higher prices. The analysis also shows that houses with higher overall quality ratings have significantly higher average sale prices.

Finally, the correlation analysis shows that overall quality has the strongest relationship with sale price, followed by living area, garage area, total basement area, and first floor area. Overall, the project identifies the main characteristics that influence house prices and provides useful insights into the housing market.

## Visualizations

### Sale Price Statistics

![Sale Price Statistics](visualizations/sale-price-statistics.png)

### Housing Market Overview

![Housing Market Overview](visualizations/housing-market-overview.png)

### Average House Characteristics

![Average House Characteristics](visualizations/average-house-characteristics.png)

### Distribution of House Prices

![Distribution of House Prices](visualizations/distribution-house-prices.png)

### Boxplot of House Prices

![Boxplot of House Prices](visualizations/boxplot-house-prices.png)

### Living Area vs. Sale Price

![Living Area vs. Sale Price](visualizations/living-space-vs-price-scatter-plot.png)

### Living Area vs. Sale Price with Regression Line

![Living Area vs. Sale Price with Regression Line](visualizations/regression-line-living-area-x-price.png)

### Average Sale Price by Number of Bedrooms

![Average Sale Price by Number of Bedrooms](visualizations/avg-price-x-number-bedrooms.png)

### Average Sale Price by Overall Quality

![Average Sale Price by Overall Quality](visualizations/avg-price-x-overall-quality.png)

### Average Sale Price by Year Built

![Average Sale Price by Year Built](visualizations/avg-price-x-year-built.png)

### Correlation with Sale Price

![Correlation with Sale Price](visualizations/correlation-variables-x-price.png)
