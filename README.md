# house price prediction
In this project i have worked on the famous dataset of california house price prediction. 
I have used StratifiedShuffleSplit so that the data is shuffled each time the train and test data is split.
The median house value is the dropped label for the training set.
I have used simpleimputer class from sckitlearn to replace the nan values with the median value.
I have used ordinal encoder for converting the categorical variables as with label encoder we can categorize a 1-d array whereas in the prior case we can categorize both feature and category i.e a 2-d array.
I also used the one hot encoder to encode the numerical categorized columns.
I have also used base estimator to create my own parameters according to the need of the data.
I have used TransformerMixin to create a customized transform and fit function by creating two more variable columns i.e. rooms per household and population per household.
I have created a pipeline for pre-processing the numerical atributes.
I have used the Column transformer class in sckitlearn to apply a specific transform to a specific column i.e. in this case i have transformed the numerical attributes by imputer and scaling. Similarly i have used the one hot encoder on the categorical column.
Similarly I have also used the Feature Union class which is alike to the Column Transformer class but just has a difference that with Feature Union we can use different transforms on the same set of input.

For training the model I have used Linear Regression to train the dataset.
The error in the model or to find the scope of improvement of the project i have used mean square error and also mean absolute error.
I have also used Decision Tree regressor, which is a class in sckitlearn which is a decision making tool which produces continuos output rather than a discrete output.
At last I have fine tuned the model using different classes such as cross validation score, random forest regressor, etc.
I have also used GridSearchCV to find out the best hyperparameters suitable for increasing the accuracy of the model by testing the data with different combination of hyperparameters.

## Special mention to Allen downey for the insight of the code and the extraordinary book Think stats 2.

 
