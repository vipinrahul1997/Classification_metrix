Classification metrics are used to evaluate how well a machine learning classification model predicts categories or classes.

Four important values
TP — True Positive

Actual delay, predicted delay.


FP — False Positive

Actual on time, predicted delay.


FN — False Negative

Actual delay, predicted on time.


TN — True Negative

Actual on time, predicted on time.

For imbalanced classification datasets, accuracy alone can be misleading. Use Precision, Recall, F1-score, and PR-AUC as appropriate.


Accuracy	     How many predictions are correct overall?
Precision    	Of predicted positives, how many were correct?
Recall	      Of actual positives, how many did we find?
F1-score	    How balanced are precision and recall? Specificity Of actual negatives, how many did we find?
ROC-AUC	      How well does the model separate the classes?
Log Loss	    How good are the predicted probabilities?
