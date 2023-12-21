# Kickstarter_analysis

## Purpose
To develop a model that can predict the success or failure of a Kickstarter campaign using data downloaded from [here](https://www.icpsr.umich.edu/web/NADAC/studies/38050)
There is also opportunity to test the model on other Kickstarter datasets like [this](https://www.kaggle.com/datasets/sripaadsrinivasan/kickstarter-campaigns-dataset) and [this one](https://www.kaggle.com/datasets/kemical/kickstarter-projects)

## About the Data
Raw data has 21 features and ~507k instances in a tsv file. Data ranges from 2009 to 2020. There are missing values and incorrect classifications like some campaigns have Failed but the Pledged amount equaled or exceeded the goal. 

## Process

I loaded the data and explored it looking for missing values, changing data types, and correcting any errors in the data (e.g. wrong Status classification). I also changed the feature names to something more concise.

I exported this dataset as csv file to import for other parts of the project - Modelling and Tableau.

The data indicated there was ~21k countries, so to correct this I used the Project Currency to get the Country. I ended up consolidated European countries as the European Union.



Next, I explored the data to identify any patterns or interesting features. I explored the data by Country, Category, Status for both counts and success rate as they had the least amount of unique values. I made some changes during this process too




