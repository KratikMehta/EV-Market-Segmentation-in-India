# EV Market Segmentation in India

This repository contains the code implementation and analysis for the Market Segmentation of the EV market in India using KMeans Clustering.

## Dataset

To perform the market segmentation for the EV market three datasets with the following sources were used:
- Charging Stations in India: https://www.kaggle.com/datasets/saketpradhan/electric-vehicle-charging-stations-in-india
- EV Population Data of USA: https://catalog.data.gov/dataset/electric-vehicle-population-data
- Indian Automobile Buying Behaviour: https://www.kaggle.com/datasets/karivedha/indian-consumers-cars-purchasing-behaviour

## Code Implementation

The code implementation involves several steps, including data loading, data preprocessing, feature engineering, exploratory data analysis (EDA), and clustering. The main libraries used in the code are `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`. 

The code is structured as follows:

1. Data Loading: The dataset is loaded into separate dataframes.
2. Data Preprocessing: Unnecessary columns are dropped, and the dataframes are merged.
3. Feature Engineering: Additional features such as weekend/weekday and day of the week are created.
4. Exploratory Data Analysis (EDA): Various visualizations are generated to gain insights into the data.
5. Clustering: KMeans clustering was used to segment the market into two segments.

## Conclusion

This project analyzed the Indian EV market and identified two potential target segments: 
1. Segment 1: younger, less well-off professionals who are looking for affordable cars
2. Segment 2: middle-aged, well-off professionals who are looking for expensive cars.

The project then develops a marketing mix for the ideal target segment, which is younger, less well-off professionals who are looking for affordable cars.

Note: This Readme file provides a summary of the project. For a more comprehensive understanding, please review the code and comments in the Jupyter Notebook. 
