# Fraud-Detection
__Detect  fraudulent credit card transactions using Decision Tree and Support Vector Machine classification models__

Using financial data to predict if a credit card transaction is fraudulent or not. It is a binary classification problem i.e a transaction belongs to the positive class (1) if it is a fraud, otherwise it belongs to the negative class (0).

Only a small portion of the transactions are often illegal, with the bulk being legal. In the current dataset, there are only 492 fraudulent transactions out of 284,807 total transactions (or 0.172% of all transactions fall into the positive class of frauds).

Note: Most feature names have been given anonymous V1, V2,... V28 designations due to confidentiality concerns. These characteristics' values are numerical and the outcome of a PCA transformation. Target variable 'Class' has two possible values: 1 in cases of fraud and 0 in all other cases. Visit this website for more details about the dataset: [DataSource](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Evaluation of the Decision Tree model
__Ran inference and got probability of fraud in test samples__

ROC-AUCCURACY score : 0.966

## Evaluate the Support Vector Machine Model
 __Ran inference and get the confidence scores__
 
SVM ROC-AUC score:   0.984
 
## Definitions
__ROC-AUC score__ is a measure used to evaluate the performance of classification machine learning models. It is the area under the ROC curve, which is a graph that displays the relationship between true positive rate (TPR) and false positive rate (FPR) at different thresholds. It can also be interpreted as the likelihood that a model will rank a randomly selected positive instance higher than a randomly selected negative one. A perfect ROC AUC score is 1, and a random classifier has a score of 0.5.

<p align="center">
  <img src="https://imgur.com/S9AyMRz.png" alt="RoC Curve" />
</p>
