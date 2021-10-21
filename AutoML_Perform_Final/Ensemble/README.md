# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                             |   Weight |
|:----------------------------------|---------:|
| 10_LightGBM                       |        1 |
| 1_Default_LightGBM                |        1 |
| 1_Default_LightGBM_GoldenFeatures |        4 |
| 20_LightGBM                       |        2 |
| 21_LightGBM                       |        2 |
| 26_Xgboost                        |        1 |
| 6_Xgboost                         |        3 |
| 9_LightGBM                        |        3 |

## Metric details
|           |      score |     threshold |
|:----------|-----------:|--------------:|
| logloss   | 0.00984768 | nan           |
| auc       | 0.999929   | nan           |
| f1        | 0.996      |   0.497755    |
| accuracy  | 0.996277   |   0.497755    |
| precision | 1          |   0.999957    |
| recall    | 1          |   5.29829e-07 |
| mcc       | 0.992518   |   0.497755    |


## Confusion matrix (at threshold=0.497755)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            67120 |              223 |
| Labeled as 1 |              246 |            58384 |

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
