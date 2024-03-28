**Overview:**

The Wisconsin-Breast Cancer (Diagnostics) dataset, commonly referred to as WBC, is a classification dataset obtained from the UCI Machine Learning Repository. It contains measurements for breast cancer cases and is used for predicting whether a tumor is benign or malignant.

**Dataset Description:**

The dataset consists of features such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.
Each instance in the dataset corresponds to a tumor sample, with measurements recorded for each feature.
The target variable is the diagnosis, which indicates whether the tumor is benign (B) or malignant (M).
Content Description:
CancerAnalysis Class: This Python class contains methods for analyzing the WBC dataset. It includes functionalities such as loading the dataset, preprocessing (handling missing values), splitting the data into training and testing sets, and implementing various machine learning algorithms for classification.

**Processes Implemented:**

Loading Dataset: The dataset is loaded using the np.genfromtxt() function from the NumPy library. Missing values (NaNs) are removed using the any() function.
Data Preprocessing: The preprocessing step involves handling missing values by removing rows containing NaNs.
Splitting Data: The dataset is split into training and testing sets based on the specified index.
Machine Learning Algorithms: Several classification algorithms are implemented for analysis, including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machine (SVM), Decision Tree, Naive Bayes, Gradient Boosting, and Polynomial Kernel SVM.
Evaluation: The performance of each algorithm is evaluated using accuracy scores on both training and testing data.

**Usage:**

To use the CancerAnalysis class, provide the path to the WBC dataset CSV file as input.
Optionally, you can specify the index to split the data into training and testing sets (default index is 469).
Call the desired method of the class to perform analysis or evaluate specific algorithms.

**Requirements:**

Python 3.x
NumPy
Scikit-learn
Matplotlib
