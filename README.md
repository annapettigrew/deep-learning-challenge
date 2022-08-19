# deep-learning-challenge

Background:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. I will use features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, I received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:


EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively



There are three steps to this analysis:

Step 1: Preprocess the Data
Using Pandas and scikit-learn’s StandardScaler(), I will preprocess the dataset. This step prepares me for Step 2, where 
I compile, train, and evaluate the neural network model.

With the data in the charity_data.csv file I will determine:

What variable(s) are the target(s) the your model?
What variable(s) are the feature(s) for the model?
The number of unique values for each column.


Step 2: Compile, Train, and Evaluate the Model
I designed a deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Then I will compile, train, and evaluate the binary classification model to calculate the model’s loss and accuracy.

Step 3: Optimize the Model
Next, I will optimize the model to achieve a target predictive accuracy higher than 75%.


I used the following methods to optimize the model:

Adjusted the input data to ensure that no variables or outliers are causing confusion in the model, such as:

Dropping more or fewer columns.
Creating more bins for rare occurrences in columns.
Increasing or decreasing the number of values for each bin.


Add more neurons to a hidden layer.
Add more hidden layers.
Use different activation functions for the hidden layers.
Add or reduce the number of epochs to the training regimen.


