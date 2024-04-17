# Chattanooga Football Club Dashboard Scripts

These scripts are designed to help you gather and analyze data from the American Soccer Analysis API to build a dashboard for monitoring Chattanooga Football Club's performance, especially after their transition from NISA to MLS Next Pro. Below is a brief overview of each script and its purpose:

## `americansocceranalysis_api.ipynb`

This notebook provides basic functionality to interact with the American Soccer Analysis API. It demonstrates how to make requests to the API endpoints and retrieve data regarding MLS Next Pro players.

## `asa_api_scraper.ipynb`

The `asa_api_scraper.ipynb` script extends the functionality of interacting with the American Soccer Analysis API. It defines functions to fetch data from different endpoints based on league and store the fetched data in pandas DataFrames. The script also includes functionality to save the fetched data as CSV files for further analysis.

## `asa_eda.ipynb`

This notebook focuses on exploratory data analysis (EDA) of the data fetched from the American Soccer Analysis API, specifically for MLS Next Pro. It loads the previously fetched data from CSV files, performs basic data exploration, and visualizes various metrics related to players, teams, and games using libraries like matplotlib and seaborn.

## `asa_metrics.ipynb`

The `asa_metrics.ipynb` script calculates and analyzes performance metrics for both teams and players based on the fetched data. It computes metrics such as goal difference, expected goals (xGoals), pass completion percentage, and points earned for teams, and metrics such as goals scored, assists, and defensive contributions for players. These metrics are used to assess the performance of both teams and individual players.

These scripts provide a solid foundation for gathering, analyzing, and visualizing data related to Chattanooga Football Club's performance in MLS Next Pro, which you can utilize to create an insightful dashboard using Tableau. Feel free to customize and extend these scripts according to your specific requirements for the dashboard.
