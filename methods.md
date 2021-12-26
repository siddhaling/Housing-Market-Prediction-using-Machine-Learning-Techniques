Methods and Result Description
Importing libraries
In the 1st section of the model, we have imported the required libraries for the further implementation of the model and loaded the dataset we are using in this model.
Cleaning the dataset and Filling the NULL values
First, cleaned the dataset by finding how many NULL values the attributes have. Then have filled these NULL values with a close approximation, which basically are the data from different rows but with similarity in some of the features.
For example, if there's a missing data in the number of bedrooms, then look up to what suburb this property is located at, then have filled the NULL value with the values of the property’s bedroom in those specific suburbs.
The same thing is also applied for outlier. Have used close approximation for outlier and replace them with upper extreme if the value is higher or lower extreme if the value is lower than the expected.
And as a result, this method is used to apply approximate values for all other NULL and outlier values of other different attributes, except for price. Since price is one of the most required attributes when checking for properties henceforth, we predict the price with Random Forest Regressor because of the accuracy that this algorithm provides us. Also, this dataset that we have is not that huge, So the training time should not be any problem.
So far, the description was provided for the sections 2nd to 8th in the model.
Analysis 
Here in the 9th section, we have analyzed 
1.	The Price fluctuations of different type of properties listed,
2.	Their geographical mapping and 
3.	The Price fluctuations in different regions 
using different types of plotting methods such us line plot and Scatter plot to have a deeper understanding of the situation provided. These graphs and the resulting observations have been noted in the Results and Graphs Document.

List of Sections
1.	IMPORTING THE REQUIRED LIBRARIES AND DATASET AS .CSV file
2.	CLEANING THE DATA 
3.	TRAINING THE DATA
4.	DATAFRAMES FOR REPLACEMENT VALUES for the required set.
5.	EDITING THE OUTLIERS
6.	TRAINING THE MODEL to check for the error variations using MSE and MAPE
7.	EDITING ALL OUTLIERS
8.	FILLING IN NULL VALUES
9.	ANALYSING THE TRAINED DATA


