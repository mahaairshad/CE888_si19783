Lab4: Modelling

Tasks:
1. Load the data from bank-additional-full.csv
2. Use a classifier (anything, but ExtraTreesClassifier with 100 estimators is the easiest option) on the data with outcome/output variable "y"
      Convert to dummies using df_dummies = pd.get_dummies(df)
      Plot histogram of the label y_yes
      Get the values and run a classifier (with outcome y_yes)
      Report the results of 10-Kfold stratified cross-validation
      Get sample importances and a confusion matrix
