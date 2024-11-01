# Data Folder

This folder contains the datasets used for the Modeling submission .Rmd file.

This includes the raw Home Credit data from Kaggle and any data files written by our code, such as the different model-results.csv files used in the model summary.

The data is saved here so that the data can be read in using simply URL filepaths, so that it's easily replicable for anyone running the code in the ntoebook.

## Contents
- `application_train.csv`: The raw dataset used for model training.
- `application_test.csv`: The raw dataset used for model testing.
- `application_train_clean.csv`: The cleaned, imbalanced dataset for model training.
- `application_test_clean.csv`: The cleaned, imbalanced dataset for model testing.
- `application_train_smote.csv`: The cleaned, SMOTE-balanced dataset for model training.
- `majority-class-baseline-model-results.csv`: Dataframe containing MCB performance vectors
