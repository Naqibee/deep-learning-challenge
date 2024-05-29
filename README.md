# deep-learning-challenge

As this challenge was designed by the Bootcamp team, here is the background of the project:

**Background:**

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are several columns that capture metadata about each organization, such as:
•	EIN and NAME—Identification columns
•	APPLICATION_TYPE—Alphabet Soup application type
•	AFFILIATION—Affiliated sector of industry
•	CLASSIFICATION—Government organization classification
•	USE_CASE—Use case for funding
•	ORGANIZATION—Organization type
•	STATUS—Active status
•	INCOME_AMT—Income classification
•	SPECIAL_CONSIDERATIONS—Special considerations for application
•	ASK_AMT—Funding amount requested
•	IS_SUCCESSFUL—Was the money used effectively

**Instructions:**

Step 1: Preprocess the Data 

o	After uploading the starter file to the Google Colab, then using the information provided in the challenge files, and following the instructions:
2.	Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
o	What variable(s) are the target(s) for your model?
o	What variable(s) are the feature(s) for your model?
3.	Drop the EIN and NAME columns.
4.	Determine the number of unique values for each column.
5.	For columns that have more than 10 unique values, determine the number of data points for each unique value.
6.	Use the number of data points for each unique value to pick a cutoff point to combine "rare" categorical variables together in a new value, Other, and then check if the replacement was successful.
7.	Use pd.get_dummies() to encode categorical variables.
8.	Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
9.	Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

Step 2: Compile, Train, and Evaluate the Model

1.	Using our class materials of TensorFlow, we will design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the feature in the dataset.
2.	Continue using the file in Google Colab in which you performed the preprocessing steps from Step 1.
3.	Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
4.	Create the first hidden layer and choose an appropriate activation function.
5.	If necessary, add a second hidden layer with an appropriate activation function.
6.	Create an output layer with an appropriate activation function.
7.	Check the structure of the model.
8.	Compile and train the model.
9.	Create a callback that saves the model's weights every five epochs.
10.	Evaluate the model using the test data to determine the loss and accuracy.
11.	Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.

Step 3: Optimize the Model

Using your knowledge of TensorFlow, optimize your model to achieve a target predictive accuracy higher than 75%.
Use any or all of the following methods to optimize your model:
•	Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
o	Dropping more or fewer columns.
o	Creating more bins for rare occurrences in columns.
o	Increasing or decreasing the number of values for each bin.
o	Add more neurons to a hidden layer.
o	Add more hidden layers.
o	Use different activation functions for the hidden layers.
o	Add or reduce the number of epochs to the training regimen.



