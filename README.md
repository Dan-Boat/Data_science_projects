# Exp.AI.ML
Consist of various machine learning and Al projects at the experimental stage. 

## 1. Stacked_ensemble
Demonstrate how to use integrated or separate stacking ensemble model for different Multi-Layer Perceptron model for simple multi-class classification probelm. The notebook uses 
sklearn datasets, tensorflow models and logistic regression form sklearn.linear model

## 2. Ensemble Regressors
Test different estimators for building ensembles trained sequentially to reduce the bias and variace of the the combined estimator. The advantage is that the individual weak models 
benefit from the high performing ones. The script uses voting regressor, which balance out the individual models weakness, and stacking regressor that uses predictions of each individual 
model to stack them together. The final estimator for stacking is optimized in cross-validation steps. Final estimators applied in this notebook includes ExtraTreeRegressor,
GradientBoosting, XGBoostRegressor, and others
The most important step is that, the ensemble model adopts different models (Beyesian regression, GLM, SVR, MLP, LassoCV, Deep Learning models) from both sklearn and tensforflow package
