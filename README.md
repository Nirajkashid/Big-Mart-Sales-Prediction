# Big-Mart-Sales-Prediction
Analytics Vidya Big Mart Sales Prediction
Sales Prediction for Big Mart Outlets

# Problem Statement
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.
Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.
The Data We have train (8523) and test (5681) data set consisting of 12 features, train data set has both input and output variable(s) We need to predict the sales for test data set.

# How would I solve the problem?
I would find the sales data for a product as detailed as possible (with as many features as possible). Select all the features with no NaN or missing data. Select the obviously important features for the model. All the other put them aside as we will be experimenting with them. Visualize the data (read through it and build some scatter, history plots for linearity and dimensionality and box plots for outliers). Build the model with different algorithms starting with the simplest and moving up to more complicated. Evaluate the performance of each algorithm. Try combining 2-3 of them and evaluate the new performance. Choose the best model and deploy it on all the test data you can find.

# What I did:
Replaced the Nans and zero values, identified outliers, feature selection and normalization - for both train and test data.
Visualised the data, studied the correlation amongst the data and chose the required features.
Built the models: I created a single model function to which I passed various different models such as Linear Regression, Decision Trees and Random Forests





