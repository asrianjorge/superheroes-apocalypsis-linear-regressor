# dataset

baraazaid/superherodb from kaggle
(the initial CSV file is not provided in this repository)

# preprocessing data

dataset contained rows with same 'Name' parameter, which used as an index. also, there were many NaN values. 

so, there was created a pipeline to process the data which contains:

1. Aggregator (for merging rows with same 'Name')
2. Preprocessor (to convert data to numeric type)
3. StandardScaler
4. Imputer (to avoid NaN values)

# model

a standard linear regressor provided by scikit-learn
