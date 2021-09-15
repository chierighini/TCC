# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model              |   Weight |
|:-------------------|---------:|
| 10_LightGBM        |        3 |
| 13_CatBoost        |        2 |
| 1_Default_LightGBM |        1 |
| 21_LightGBM        |       15 |
| 22_LightGBM        |        2 |
| 26_LightGBM        |        5 |

## Metric details
|           |      score |     threshold |
|:----------|-----------:|--------------:|
| logloss   | 0.00236729 | nan           |
| auc       | 0.999996   | nan           |
| f1        | 0.999199   |   0.5         |
| accuracy  | 0.999254   |   0.5         |
| precision | 1          |   0.999975    |
| recall    | 1          |   1.83948e-07 |
| mcc       | 0.998501   |   0.5         |


## Confusion matrix (at threshold=0.5)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            67274 |               69 |
| Labeled as 1 |               25 |            58605 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
