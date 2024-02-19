# Rain_Fall_Prediction
Final Project for Python for AI course

Problem Statement 

Predicting rainfall accurately for a region is very important for improving crop yields, optimizing use of existing water resources and effectively planning water infrastructure projects. Machine learning is frequently used for the task of predicting rainfall in a given area based on historical data. 

Solution

-Obtain data source
-Explore data source and learn about it
-Clean data if necessary
-Visualize data 
-Create a model– Linear Regression
-Training the model and evaluating its performance


Data

The dataset is a public weather dataset from Austin, Texas available on Kaggle.
Dataset contains data for every date from 2013-12-21 to 2017-07-31, it has 21 columns and 1320 rows. 
Dataset rarely comes in ready to use state, in order to have structured and workable data we need to clean the data. Some common cleaning includes parsing, converting to data type which is required for our algorithm, removing unnecessary data, etc. in our case Data is mostly complete but some values for few fields are missing and ‘PrecipitationSumInches’ column has ‘T’ if precipitation is in Trace. We need to convert all ‘T’ and missing values to numbers.

