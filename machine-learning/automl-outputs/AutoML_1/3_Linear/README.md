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

3.8 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.21812   |
| MSE      | 0.0964732 |
| RMSE     | 0.310601  |
| R2       | 0.612556  |
| MAPE     | 0.0170603 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |  0.63891    |
| DistancePark              |  0.317638   |
| Eircode                   |  0.20012    |
| intercept                 |  0.150934   |
| Year                      |  0.0749246  |
| Longitude                 |  0.0556341  |
| Month                     |  0.00188969 |
| Property Size Description | -0.00331157 |
| DistanceSchool            | -0.0178914  |
| DistanceSecSchool         | -0.0291508  |
| Latitude                  | -0.0374394  |
| Town                      | -0.047479   |
| Apartment                 | -0.219676   |
| DistanceIFSC              | -0.233283   |
| UsedProperty              | -0.265213   |


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
