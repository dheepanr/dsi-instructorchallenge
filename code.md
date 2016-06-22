
## Instructor Task

## Part I - Logistic Regression
### Dataset 
 - Here is the dataset (https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/datasets/breast-cancer.csv)
 - Here is a description of the data. Ignore column 0 as it is merely the ID of a patient record.
 - (https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names)
### 1. Read in the data

### 2. Separate the data into feature and target

### 3. Create and evaluate using cross_val_score and 5 folds.

### 4. Get a classification report to identify type 1, type 2 errors. 
 - Use train_test_split to run your model once, with a test size of 0.33
 - Make preidctions on the test set
 - Compare the predictions to the answers to determine the classification report

### 5. Scale the data and see if that improves the score"

### 6. Tune the model using automated parametrics grid search via LogisticRegressionCV. 
 Explain your intuition behind what is being tuned.

 - Q: What should we do to prevent overfitting so our model generalizes well to the test data?
 - Q: What was the best C?

### 7. Create Two Plots that describe the data and discuss your results

### 8. Provide a one-sentence summary for a non-technical audience. Then provide a longer paragraph-length technical explanation.

## Part II - Ensemble Methods

## Dataset
 Your dataset will be the breast cancer dataset. You can load it directly from scikit-learn using the load_breast_cancer function.

### 1. Read in the data

### 2. Separate the data into feature and target

### 3. Build and initial model

### 4. Integrate your model into a pipeline

### 5. Evaluate your performance utilizing grid search with 5-fold cross validation. 


