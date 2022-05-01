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

3.6 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.2394    |
| MSE      | 0.126667  |
| RMSE     | 0.355903  |
| R2       | 0.629959  |
| MAPE     | 0.0187438 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |   0.692324  |
| DistancePark              |   0.234023  |
| Eircode                   |   0.102872  |
| Longitude                 |   0.0975082 |
| Year                      |   0.0704434 |
| Property Size Description |   0.0392735 |
| intercept                 |   0.0347805 |
| Month                     |   0.0278349 |
| DistanceSchool            |   0.0270875 |
| UsedProperty              |   0.0117395 |
| DistanceSecSchool         |  -0.0276785 |
| Town                      |  -0.054402  |
| Latitude                  |  -0.0777814 |
| DistanceIFSC              |  -0.148964  |
| Apartment                 |  -0.377747  |


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
