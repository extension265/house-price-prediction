# house price prediction
In this project i have worked on the famous dataset of california house price prediction. 
I have used StratifiedShuffleSplit so that the data is shuffled each time the train and test data is split.
The median house value is the dropped label for the training set.
I have used simpleimputer class from sckitlearn to replace the nan values with the median value.
I have used ordinal encoder for converting the categorical variables as with label encoder we can categorize a 1-d array whereas in the prior case we can categorize both feature and category i.e a 2-d array.
I also used the one hot encoder to encode the numerical categorized columns.
I have also used base estimator to create my own parameters according to the need of the data.
I have used TransformerMixin to create a customized transform and fit function by creating two more variable columns i.e. rooms per household and population per household.

 
