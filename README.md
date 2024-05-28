# README

These projects explore techniques such as feature extraction, normalization, and various machine learning algorithms for classification and clustering of biomedical signals, specifically from CTG and ECG data. This data helps us understand methods on improving the accuracy of diagnosing, recognizing, and predicting medical conditions and anomalies through the use of signal processing.


### Overview

The first task involves classifying letters from a dataset with 617 features. Various models are trained on the full feature set and on reduced feature sets obtained using Principal Component Analysis (PCA). In the second task, we aim to classify the state of the fetus from a dataset containing sound features. The dataset includes 21 features and a target variable representing the fetal state. Different machine learning models are trained and evaluated to achieve the best classification performance.


### Methods

The different models are trained and evaluated using different feature sets and reduction techniques:

1. **K-Nearest Neighbors (KNN)** - Applied to both all features and PCA-reduced features.
2. **Support Vector Machine (SVM)** - Tested with linear, RBF, poly, and sigmoid kernels on PCA-reduced features.
3. **Logistic Regression** - Used on PCA-reduced features.
4. **Naive Bayes** - Implemented for classification tasks.

#### Evaluation Metrics

The models are evaluated using confusion matrices and the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

### Results

The SVM and Logistic Regression models outperformed the KNN models, especially on the earlier and middle letters. For task two, the SVM with a kernel transformation and One-vs-Rest strategy performed the best across all metrics, followed by the Linear SVM, Logistic Regression, and Naive Bayes models. The application of various machine learning models and techniques on two distinct classification tasks showcases the steps necessary to achieve optimal performance in different machine learning scenarios.

###Project Report
The full report of the software implementation of this project can be found in the .pdf files. To view the report, please download the file and open it locally. As for the python implementation, you can view it in Jupyter Notebook directly or use the .py files to open it loacally.

