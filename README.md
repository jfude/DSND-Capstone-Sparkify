# DSND-Capstone-Sparkify
Prediction of churn for a fictional music streaming service.

## Introduction
Using a small sample of data from a hypothetical music streaming service (similar to Pandora or Spotify), we attempt to develop a model to anticipate **churn**, i.e. cancellation of the service. The analysis is performed using pySpark. A blog post outlining the analysis in this repository can be found [here](https://medium.com/@jaalfordii/predicting-churn-for-sparkify-75c862e3e286).

## Files
  * dsnd_capstone_sparkify.ipynb -- *The notebook containing the analysis*
  * dsnd_capstone_sparkify.html  -- *HTML print of the notebook*
  
## Analysis Outline
  1. **Initial Look at Data** -- *data shape, field descriptions, definition of churn*
  2. **Exploratory Analysis and Feature Discovery** -- *Field by field breakdown and analysis*
  3. **Feature Engineering** -- *selection and build of feature matrix, train/test split*
  4. **Initial Model Runs and Comparison** -- *DecisionTree, RandomForest, Multiclass prediction*
  5. **Model Tuning** -- *hyperparameters, evaluators* 
  6. **Final Reflections**
  
## Result Summary
  The data provided was very unbalanced with only 52 out of 225 users in churn. We used the F1 score as a guiding
  metric, but were only able to achieve 34% for this score. On the other hand, eight out of the eleven cancelling users
  and 90 out of 118 staying users in the test set were predicted correctly, a somewhat decent result.  
