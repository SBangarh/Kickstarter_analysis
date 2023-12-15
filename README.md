# Kickstarter_analysis

## Purpose
To develop a model that can predict the success or failure of a Kickstarter campaign using data downloaded from [here](https://www.icpsr.umich.edu/web/NADAC/studies/38050)
There is also opportunity to test the model on other Kickstarter datasets like [this](https://www.kaggle.com/datasets/sripaadsrinivasan/kickstarter-campaigns-dataset) and [this one](https://www.kaggle.com/datasets/kemical/kickstarter-projects)

## About the Data
Raw data has 21 features and ~507k instances in a tsv file. Data ranges from 2009 to 2020.

## Process
I loaded the data in str data type for ease and decided I would alter data types later. I analyzed how the features were formatted and had to clean up some regular expressions, feature names, location data (i.e. Country) as initial analysis indicated there were over 21k countries. I used the project currency to map the countries and consolidated European countries as Europe. 

Next, I looked at how the data was distributed across some features in terms of campaign counts and success rate. I also explored the data distribution with histograms and boxplots to determine how best to transform the data prior to modelling. 

