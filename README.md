# Decision-tree-based-income-prediction
This project builds a decision tree to predict income of an individual of the population based on various features.

# Data set
The data set consists of 32,561 rows of along with 15 columns that contain features about individuals such as their age, working class, marital status, occupation, native country etc.

# Data preprocessing
Several missing values in the data are denoted by a '?' symbol. As these correspond to about 5% of the dataset, these are dropped from the data set. LabelEncoder() sub-class of SkLearn's preprocessing class is used to encode categorical variables as numerical values.

# Model building
The data set is divided into training and test data sets. SkLearn's DecisionTreeClassifier() class is used to build a decision tree with a max depth of 5. A preliminary accuracy of 85% is achieved with this decision tree model. The decision tree is plotted for visualisation.

# Hyperparameter tuning
The hyperparaneters max depth, min_samples_split and min_samples_leaf are tuned using SkLearn's GridSearchCV() class to find the optimal values of these hyperparameters. A final accuracy of 85% is achieved with the parameter values arrived at through parameter tuning.
