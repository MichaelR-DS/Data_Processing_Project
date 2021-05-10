# Data Processing Project
In this short project I combined, cleaned and analysed two datasets; weekly sales/weighted prices for cheddar and weekly gasoline prices. Datasets are sourced from the U.S. Dept Of Agriculture and the U.S. Energy Information Administration.

## Libraries Used
* Matplotlib
* Seaborn
* Pandas
* Numpy

## Goal
My aim in this project was to prepare a dataset which could be used for modelling. In particular, to predict the number of sales or the price of cheddar (sold in 40-pound blocks) based on fuel prices.

## Data Processing
I combined the two datasets by:

* selecting the time interval which they intersect
* converting the dates to datetime and merging the two datasets based on their nearest date (of the week)

After making sure there were no missing values or errors in the resulting dataset, I analysed the data.

## Data Analysis

* compared the correlation of the features; it appeared that the number of sales were not dependent on the prices of fuel, however it might be valuable to further investigate the relationship between the price of cheddar and the prices of fuel.
* plotted the sales and the price of cheddar over the period 2012-2018.
* compared the sales and price of cheddar to which day of the week the prices were recorded. No significant difference was found.

Link to data: https://www.kaggle.com/sohier/weekly-dairy-product-prices?select=Datamart-Export_DY_WK100-500+Pound+Barrel+Cheddar+Cheese+Prices%2C+Sales%2C+and+Moisture+Content_20170829_122601.csv
https://www.kaggle.com/mruanova/us-gasoline-and-diesel-retail-prices-19952021
