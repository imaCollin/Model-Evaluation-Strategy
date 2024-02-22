# Model-Evaluation-Strategy
## Selected model evaluation index:
### 1. Based on accuracy
The ratio of accurately classified forecasts and the total number of forecasts will be evaluated.

$$Accuracy = （TP+TF）/ (TP+TF+FP+FN)$$

Where TP indicates that both the actual category and the model prediction are positive. TN indicates that both the actual category and the model prediction are negative. FP indicates that the model predicts a positive category while the actual category is negative. FN indicates a positive category when the model predicts a negative category.

<img width="369" alt="image" src="https://github.com/imaCollin/Model-Evaluation-Strategy/assets/127849702/ad621808-897e-4d6f-bc4d-fe1359ff12bc">

_Binary Classification Confusion Matrix in Machine Leaarning_

MCC is a single-valued classification measure that helps summarize the confusion matrix. The MCC describes the correlation coefficient between the actual and predicted samples, with values ranging from [-1, 1]. An MCC equal to 1 indicates a perfect positive correlation. In contrast, when the classifier misclassifies, the value -1 is obtained, indicating a perfect negative correlation. The robustness of MCC to class imbalance is superior to the accuracy based measures mentioned earlier.

$MCC = (TPTN - FPFN)/\sqrt{(TP+FP)(TP+FN)(TN+FP)(TN+FN)}$

### 2. Based on Error
An error-based metric measuring the error between predicted and actual values is one of the most effective ways to measure forecasting performance, where smaller errors indicate better results. 

<img width="388" alt="image" src="https://github.com/imaCollin/Model-Evaluation-Strategy/assets/127849702/aa74430e-a9f2-439f-b9fb-ae9161cb9a94">

### Based on Return Ratio
a. Return Ratio
b. Sharperatio
