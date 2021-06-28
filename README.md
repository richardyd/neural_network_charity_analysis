# Neural Network Charity Analysis
## Module 19 - Challenge

# Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python and analyze, classify the success of charitable donations.
For this analysis we will utilize the followingg methods:
- preparing the data for the neural network model;
- compiling, training and assessing the accuracy of the model;
- optimizing the model.
## Dataset and Technology:
Dataset: charity_data.csv
Software: VS Code 1.57.1 with Python 3.9.5 64-bit, Anaconda Navigator 2.03
## Results
Columns EIN and NAME have been dropped from the dataframe. We converted the columns into features and targets arrays. The column IS_SUCCESSFUL was designated a target.
The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
The remaining data was split into training and testing datasets. We then applied standardization to the features.
We defined the model - deep neural net, that is the number of input features and hidden nodes for each layer. We checked the structure of the mode.
Our evaluation of the model using test data show a low accuracy in our view: 0.4671.
We also compiled the model using the 'adam' optimizer . The accuracy achieved was:  accuracy: 0.7248.
## Summary
With this model, the highest accuracy we had achieved was 72%. To increase the accuracy we could have used another model and hopefully achieve such goad. Random forest could be this model.