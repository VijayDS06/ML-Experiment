# Summary of 5_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.336193 | nan         |
| auc       | 0.929975 | nan         |
| f1        | 0.897638 |   0.554742  |
| accuracy  | 0.886957 |   0.554742  |
| precision | 0.967742 |   0.943643  |
| recall    | 1        |   0.0480973 |
| mcc       | 0.772734 |   0.631675  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.336193 |  nan        |
| auc       | 0.929975 |  nan        |
| f1        | 0.897638 |    0.554742 |
| accuracy  | 0.886957 |    0.554742 |
| precision | 0.897638 |    0.554742 |
| recall    | 0.897638 |    0.554742 |
| mcc       | 0.771424 |    0.554742 |


## Confusion matrix (at threshold=0.554742)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               90 |               13 |
| Labeled as 1 |               13 |              114 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
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
