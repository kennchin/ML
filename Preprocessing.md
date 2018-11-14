# Preprocessing for numeric features 
* Usually Non-tree-based model depends on preprocessing. 
* Some of the most common preprocessing:
  1. MinMaxScaler - convert to range of [0,1]
  2. StandardScaler - convert to mean of 0 and standard deviation of 1
  3. Rank - set space between sorted value to be equal
  4. np.log(1+x) and np.sqrt(1+x)
# Preprocessing for categorical features
* Common for tree-based model:
  1. Label encoding - maps categories to numbers (sklearn.preprocessing.LabelEncoder)
  2. Frequency encoding - maps categories to frequencies 
* Common for non-tree-based model;
  1. One-hot encoding - create dummy variables (pandas.get_dummies/sklearn.preprocessing.OneHotEncoder)
# Feature Generation for Datetime
* Break down date time into days, weeks, hours to look for periodicity, time since, and time difference as new feature.
