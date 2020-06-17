# GOLD PRICE ANALYSIS AND PREDICTION

### clone the project and unzip the project files

### run the requirement.txt file and install all needed packages.

### run the predict.py file

### DATASET:

The data set has been gotten from the “World
Gold Council’s” website. This dataset is for the global gold prices from 1978 to 2020.
and Y-finance python package is used to retrieve the already trained data. and I have used only 2008 to 2019 data set.

### PREPROCESSING:

We preprocess all the data by using basic techniques like dropping all the rows with
missing values (there weren’t any!). The most preprocessing was done to the dates,
since the data was collected from different sources, the dates were in different formats
and they were formatted to a common format which would be understood by
matplotlib for plotting it appropriately.


### Training & Testing

80% data used for training purpose and 20% data is used to testing purpose.


### CREATING A MODEL:
● Linear Regression

We try to create a simple regression model. It is a linear regression model with
input parameters as the moving average of the past Gold ETF Prize, 3 days moving average and 9 days moving average.

● predict the prices and fit the training data

● Check the project accuracy


### OBSERVATIONS and CONCLUSION:

We now have a model which can predict the gold price with almost 98% accuracy and
have found an interesting correlation between the market price of gold and the
wedding season in India.


For future work, we can use and build upon our existing model to build a
recommendation system suggesting the users the right time to buy and sell gold for
people who take interest in investing in gold.

## Credits

* [Rohit Sharma](https://github.com/Rohit45-rs)
