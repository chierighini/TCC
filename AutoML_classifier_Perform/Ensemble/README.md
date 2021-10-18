# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                      |   Weight |
|:---------------------------|---------:|
| 10_LightGBM                |        3 |
| 10_LightGBM_GoldenFeatures |        3 |
| 24_LightGBM                |        9 |
| 25_LightGBM                |        8 |

## Metric details
|           |      score |     threshold |
|:----------|-----------:|--------------:|
| logloss   | 0.00233978 | nan           |
| auc       | 0.999996   | nan           |
| f1        | 0.999207   |   0.5         |
| accuracy  | 0.999262   |   0.5         |
| precision | 1          |   0.999982    |
| recall    | 1          |   5.68053e-08 |
| mcc       | 0.998517   |   0.5         |


## Confusion matrix (at threshold=0.5)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            67272 |               71 |
| Labeled as 1 |               22 |            58608 |

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
