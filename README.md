# World_Development_Indicators_for_India-1960-2021-_Analysis
This project appears to be a data analysis and visualization task focusing on World Development Indicators (WDI) data for India spanning from 1960 to 2021. Here's a summary of the steps involved:

Data Import: The project starts with importing necessary libraries such as Pandas, NumPy, Seaborn, and Matplotlib, and then loads the dataset using Pandas' read_csv() function.

Data Exploration and Cleaning:

Initial exploration using head(), info(), and isnull().sum() to understand the dataset's structure and identify missing values.
Summary statistics are calculated using describe() to get an overview of numerical features.
Exploration of unique indicators and years.
Filtering numerical columns for correlation analysis and visualization.
Handling missing values using SimpleImputer.
Data Visualization:

Correlation heatmap between numerical features.
Scatter plot visualizing GDP per capita against life expectancy.
Histogram and box plot showing the distribution of life expectancy and GDP per capita.
Bar plot displaying the top indicators by average value.
Line plot illustrating GDP per capita trends over time.
Pie chart showing the distribution of employment indicators.
Pair plot for a visual comparison between GDP per capita, life expectancy, and unemployment.
Various other visualizations like bar plots, box plots, and violin plots to analyze different aspects of the data.
Statistical Analysis:

Calculation of mean squared error (MSE) for a linear regression model predicting life expectancy based on GDP per capita.
SQL queries to extract top indicators and years with the highest average values.
Conclusion:

The project ends with a brief conclusion, summarizing key insights derived from the analysis.
This project showcases proficiency in data manipulation, visualization, and analysis using Python libraries and SQL. It demonstrates the ability to derive insights from complex datasets and communicate findings effectively through visualizations and statistical summaries.
