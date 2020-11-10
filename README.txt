Project name: Predict survival of Hepatitis patients

Goal: Preprocess the data and build a machine learning model to predict weather new patients will survive hepatitis or not, based on their symptoms.

Skills required:
  - Data preprocessing such as missing value imputation, and outlier detection
  - Python programming
  - Understanding Numpy, Pandas, Seaborn libraries
  - Understanding statistical concepts such as correlation, scatter plots, and histograms
  - Classification algorithms such as neural networks, logistic regression, SVM, and random forests

Challenges:
  - Many features have missing values
  - There are only 155 samples, each containing 19 features
  - Class imbalance: Most of the data belongs to patients who survived

Results:
  - Since the class is imbalanced, and we want to minimize false negatives more than false positives, Recall is the most important measurement because it is sensitive to false negatives, and then f-score is important because it considers both false negatives and false positives. Then Precision, and finally, Accuracy which is irrelevant in this problem.
  - By running the notebook multiple times, it becomes clear that neural networks and logistic regression produce the best results, and should be considered for deployment.

Data used from:
https://archive.ics.uci.edu/ml/datasets/Hepatitis