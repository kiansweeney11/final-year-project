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

4.0 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.237114  |
| MSE      | 0.109043  |
| RMSE     | 0.330217  |
| R2       | 0.666147  |
| MAPE     | 0.0184849 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |   0.658991  |
| DistancePark              |   0.342313  |
| Eircode                   |   0.16743   |
| Longitude                 |   0.0589763 |
| Year                      |   0.042668  |
| Property Size Description |   0.0407597 |
| intercept                 |   0.0334808 |
| Month                     |   0.0261374 |
| DistanceSecSchool         |  -0.0156604 |
| UsedProperty              |  -0.0335048 |
| DistanceSchool            |  -0.0381165 |
| Town                      |  -0.0594508 |
| Latitude                  |  -0.0898062 |
| Apartment                 |  -0.14598   |
| DistanceIFSC              |  -0.202558  |


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
