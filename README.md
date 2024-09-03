# SpaceX Falcon 9 Launch Data Analysis

**Date:** 03/09/2024


## Introduction

This capstone project is part of the **IBM Data Science Professional Certificate** course by IBM. The goal of this project is to analyze SpaceX Falcon 9 launch data and build predictive models to forecast rocket landing success. The analysis covers data collection, data wrangling, exploratory data analysis (EDA), interactive visualizations, and predictive modeling.

## Project Files & Structures

| No. | Files | Description |
| --- | ----- | ----------- |
| 1   | `SpaceX_Data_Collection_API.ipynb` | This Python script fetches SpaceX launch data using the SpaceX REST API. The data includes details about rocket launches, payloads, and landing outcomes. |
| 2   | `Data_Collection_with_Web_Scraping.ipynb` | This script performs web scraping on SpaceX-related [Wikipedia](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches) pages using the BeautifulSoup library. It extracts additional launch data not available via the API. |
| 3   | `SpaceX_Data_Wrangling.ipynb` | This script handles data cleaning and preprocessing, addressing null values, filtering data, and creating a clean dataset ready for analysis. |
| 4   | `EDA_with_SQL_using_SQLite.ipynb` | This notebook explores the SpaceX data using SQL queries in SQLite. It focuses on key metrics such as launch outcomes, payload mass, and booster performance. |
| 5   | `EDA_with_Pandas_and_Matplotlib.ipynb` | This notebook performs exploratory data analysis (EDA) using Pandas for data manipulation and Matplotlib for visualization. It uncovers trends and relationships in the data. |
| 6   | `SpaceX_Folium_Dashboard.ipynb` | This script creates an interactive map using Folium, displaying SpaceX launch sites, and analyzing their proximity to coastlines. |
| 7   | `SpaceX_Plotly_Dashboard`/`spacex_dash_app.py`| This folder contains a Plotly Dash application that provides interactive visualizations of SpaceX launch data. Users can filter data and explore different aspects of rocket launches. |
| 8   | `SpaceX_Machine_Learning_Prediction.ipynb` | This notebook builds and evaluates various classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict the success of rocket landings. The Decision Tree model achieved the highest accuracy. |

## How to Run the Dash Application

For detailed instructions on how to run the SpaceX Plotly Dashboard, please refer to the `how-to-start.md` file located inside the `SpaceX_Dash` folder.

## Results and Insights

This project covers various analyses and predictive modeling tasks, including:
- Data Exploration: Insightful visualizations to understand patterns in rocket launches and landings.
- Predictive Analysis: Building and evaluating machine learning models to predict rocket landing success.
- Interactive Dashboards: Providing a user-friendly interface for exploring SpaceX launch data.

## External References

- SpaceX REST API: [SpaceX API Documentation](https://github.com/r-spacex/SpaceX-API)
- IBM Data Science Professional Certificate: [Course Link](https://www.coursera.org/professional-certificates/ibm-data-science)
