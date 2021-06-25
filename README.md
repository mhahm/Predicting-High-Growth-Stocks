# Predicting-High-Growth-Stocks Using 10-K Data

What do the financial fundamentals of companies tell us in predicting stock price returns?

In this project, I build a machine learning model, trained on financial data derived from 10-K filings, to classify stocks from the S&P 500 that have a 20% rate of return in a 1 year period.
![image](https://github.com/mhahm/capstone2_update/blob/master/Images/growth_stock_image.jpg)

# Table of Contents
---------------------------------
## Data Wrangling
[Data Acquisition and Initial Wrangling](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Data%20Wrangling.ipynb)
* Loading of Data
* Merging of Datasets
* Creation of target variable: calculate percent returns and determine threshold
* Creation of csv file: [merged data set with target](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/dataset_wrangled/target.csv)

## Cleaningm Engineering, and Exploratory Data Analysis (EDA)
[Missing Values, Feature Engineering, EDA](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Missing%20Values%2C%20Feature%20Engineering%2C%20and%20EDA.ipynb)
* Further preprocessing and exploration - missing values
* Engineering new features from pre-existing features
* Descriptive Statistics
* Visualizations of distributions
* Creation of [clean data set](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/dataset_wrangled/df_clean.csv) ready for modeling

## Machine Learning Modeling
[Modeling and Evaluation on All Features](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Preprocessing%2C%20Modeling%2C%20and%20Evaluation%20on%20All%20Features.ipynb)
* Creation of various supervised classification models
* Model Optimization
* Evaluation of models through various classification metrics

[Feature Selection](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Feature%20Selection.ipynb)
* Correlation of predictors with target variable
    * Removed multicollinearity
* SelectKBest and Mutual Information
    * Top 30 Scores

Modeling and Evaluation on Subset of Features
* Modeling and evaluation steps repeated but for a subset of features chosen through feature selection
* [Modeling on Correlations Subset](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Modeling%20Features%20Reduced%20by%20Correlations.ipynb)
* [Modeling on Mutual Information Subset](https://github.com/mhahm/Predicting-High-Growth-Stocks/blob/master/Notebooks/Modeling%20Features%20Reduced%20by%20Mutual%20Information.ipynb)

#### NOTE: If the notebooks previews do not render properly, please paste the github links to each notebook into [nbviewer](https://nbviewer.jupyter.org)

## Summary and Report
[Project Report and Documentation](https://docs.google.com/document/d/16pZCxDqiiWnb7IyoF_ppNdPrdFw2rydIyCvkv4QAHQQ/edit#heading=h.lk5aij34viji)

[Slide Deck](https://docs.google.com/presentation/d/1lrUM1O_O4hiXsD5zag52jg8mOsVUH686zSqO55Q9R1A/edit?usp=sharing)
