# Leading_Causes_SQL_Analysis
Data analysis of the top ten leading causes of death in the United States using PostgreSQL.

Project Title: Analyzing Trends in the Top Ten Leading Causes of Death in the United States (1999–2017)

Overview:
This project aims to analyze and visualize trends in the 10 leading causes of death in the United States between the years 1999 and 2017. By examining historical data, we aim to uncover insights in the changing patterns of mortality rates of American citizens and identify significant trends or shifts in causes of death over time.

Data Source:
This dataset is provided by the U.S. Department of Health & Human Services, published by the Centers for Disease Control and Prevention, and maintained by the National Center for Health Statistics. 

The dataset presents the 10 leading causes of deaths for each state and the District of Columbia and their age-adjusted death rates. More information on computing the age-adjusted death rates can be found at the following URL address: https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states.

Analysis Steps:
1. Data Cleaning and Preparation: removal of unnecessary columns, creation of tables for individual causes and for the United States as a whole.
2. Exploratory Data Analysis (EDA): explore the distribution of mortality rates for each cause of death; identify outliers, trends, and patterns over time.
3. Trend Analysis: compute annual mortality rates and analyze trends for each cause of death, identify significant changes in mortality patterns across different years.
4. Visualization: create line charts to illustrate trends and comparisons across causes of death and years.
5. Insights and Interpretation: derive insights from analysis regarding changes in mortality rates, notable trends, and potential implications for public health policies.

Tools:
PgAdmin 4 (PostgreSQL) used for:
1. Data cleaning, transformation, and analysis tasks
2. Creation of tables to store and organize the mortality data by year, cause of death, state, number of deaths, and mortality rates.
3. Execution of SQL queries for data aggregation, filtering, and computing summary statistics necessary for trend analysis.
