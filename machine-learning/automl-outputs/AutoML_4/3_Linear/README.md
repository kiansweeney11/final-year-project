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

3.5 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.18036   |
| MSE      | 0.0778241 |
| RMSE     | 0.27897   |
| R2       | 0.660881  |
| MAPE     | 0.0141431 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                   |   Learner_1 |
|:--------------------------|------------:|
| Neighbourhood             |  0.589044   |
| Eircode                   |  0.397675   |
| DistancePark              |  0.280186   |
| intercept                 |  0.228662   |
| Longitude                 |  0.036852   |
| Property Size Description |  0.014681   |
| Latitude                  |  0.0110881  |
| Month                     |  0.00899669 |
| DistanceSchool            |  0.00839795 |
| Year                      | -0.0517233  |
| DistanceSecSchool         | -0.0827395  |
| Town                      | -0.166069   |
| DistanceIFSC              | -0.226014   |
| Apartment                 | -0.39487    |
| UsedProperty              | -0.399768   |


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
