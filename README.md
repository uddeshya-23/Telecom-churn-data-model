# Telecom-churn-data-model
Preprocess data-Conduct appropriate exploratory analysis to extract useful insights-Reduce the number of variables using PCA-LR
Preprocess data (convert columns to appropriate formats, handle missing values, etc.)

Conducted appropriate exploratory analysis to extract useful insights (whether directly useful for business or for eventual modelling/feature engineering).

Derived new features.

Reduce the number of variables using PCA.

Train a variety of models, tune model hyperparameters, etc. (handle class imbalance using appropriate techniques).

Evaluated the models using appropriate evaluation metrics. Note that it is more important to identify churners than the non-churners accurately - choose an appropriate evaluation metric which reflects this business goal.

Finally, choosen a model based on some evaluation metric.

 

The above model is able to achieve one of the two goals - to predict customers who will churn. You can’t use the above model to identify the important features for churn. That’s because PCA usually creates components which are not easy to interpret.

 

Therefore, there is another model with the main objective of identifying important predictor attributes which help the business understand indicators of churn. A good choice to identify important variables is a logistic regression model or a model from the tree family. In case of logistic regression,handled multi-collinearity.

 

After identifying important predictors, display them visually - used plots, summary tables etc. - whatever you think best conveys the importance of features.
