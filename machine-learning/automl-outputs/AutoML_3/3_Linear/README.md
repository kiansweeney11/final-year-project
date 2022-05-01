# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

4.6 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.173318  |
| MSE      | 0.077211  |
| RMSE     | 0.277869  |
| R2       | 0.574798  |
| MAPE     | 0.0135961 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |  0.658945   |
| Eircode                   |  0.411449   |
| DistancePark              |  0.244847   |
| intercept                 |  0.211535   |
| Latitude                  |  0.0677189  |
| Year                      |  0.0174846  |
| Property Size Description |  0.0157683  |
| Month                     | -0.00679068 |
| Longitude                 | -0.0194015  |
| DistanceSchool            | -0.0274927  |
| DistanceSecSchool         | -0.051699   |
| Town                      | -0.187778   |
| DistanceIFSC              | -0.260729   |
| Apartment                 | -0.425347   |
| UsedProperty              | -0.468966   |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
