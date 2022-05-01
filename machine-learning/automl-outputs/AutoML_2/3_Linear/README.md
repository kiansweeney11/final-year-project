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

4.2 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.168791  |
| MSE      | 0.0674894 |
| RMSE     | 0.259787  |
| R2       | 0.647989  |
| MAPE     | 0.0133179 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |  0.598244   |
| Eircode                   |  0.358429   |
| DistancePark              |  0.19345    |
| intercept                 |  0.176498   |
| Latitude                  |  0.104667   |
| Year                      |  0.0155755  |
| DistanceSecSchool         |  0.0109935  |
| Property Size Description |  0.00103967 |
| Month                     | -0.0050665  |
| Longitude                 | -0.0540689  |
| DistanceSchool            | -0.0562524  |
| Town                      | -0.0734525  |
| DistanceIFSC              | -0.276712   |
| Apartment                 | -0.387116   |
| UsedProperty              | -0.475029   |


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
