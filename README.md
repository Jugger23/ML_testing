# ML_testing

Repository for investigating sklearn and tensorflow methods based on online data.

## Progress theoretical application

Tracking progress of completly self-written ML algorithms.

### lin_regression_manual.ipynb
 - Input data with pandas
 - Investigate data with DataWrangler
 - *def regression_fcn*: Use linear Regression model
 - *def loss_function*: Use square root function for loss function
 - *def gradient*: Calculating gradients manually
 - *main*: apply functions and iterate to local optimum with *def gradient*

## Progresss with sklearn

Tracking the progress in different Python scripts.

### lin_regression_sklearn.ipynb
 - Input data with pandas
 - Investigate data with DataWrangler
 - Shuffle data with *ShuffleSplit*
 - Apply *Linear Regression* Model of *sklearn*
 - Determine best model of cross validation with validation set
 - Plot linear Model with test data
 - Calculate correlation coefficients
 - Estimate p-values for probability test and significance test
 - Apply to another data set with *KFold*

### neuronalnetwork_sklearn.ipynb
 - Input data with pandas
 - Investigate data with DataWrangler
 - Apply *MLPClassifier*
 - Calculate ML metrices

### sklearn.ipynb
 - Input official data of breat cancer with pandas
 - Investigate data with DataWrangler
 - Plot data
 - Split data in train, valid and test sets
 - Use *LogisticRegression*, *DecisionTreeClassifier* or *RandomForestClassifier* to classify breast cancer
 - Determine ML metrices
   
   
## Progress with tensorflow

Tracking the progress in different Python scripts.

### compare_sklearn_tensorflow.ipynb
 - Input official data of titanic dataset
 - Cleaning dataset
 - Plotting variance plots with seaborn
 - Replacing string sex data with binary data
 - Calculating linear correlation coeffient
 - Create new feature *relatives*
 - Select, split and scale data
 - Use naiveBayes model *GaussianNB*
 - Calculate ML metrices
 - Import tensorflow 3-layer Deep-Dense-Model with ReLu, ReLu and Sigmoid activation functions
 - Use ADAMS optimizer
 - Apply Tensorboard
 - Fit model and print ML metrices
 - Compare to sklearn results
   
