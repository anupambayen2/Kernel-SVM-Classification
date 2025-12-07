Project Summary: Customer Purchase Prediction Using Kernel SVM Classification

This project uses Kernel Support Vector Machine (Kernel SVM) to predict whether a user will purchase a product based on their demographic and salary information. This is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To build a classification model that can handle complex, non-linear patterns by mapping data into a higher-dimensional space using kernel functions.

📊 Dataset

Dataset used: Social_Network_Ads.csv

Features:

Age

Estimated Salary

Target Variable:

Purchased (0 = No, 1 = Yes)

This dataset is ideal for demonstrating the power of non-linear kernels.

🛠️ Steps Performed

Loaded and preprocessed data

Selected input features and target variable

Splitted the dataset into training and testing sets

Applied feature scaling (very important for SVM)

Trained a Kernel SVM classifier (using RBF kernel)

Predicted customer purchase outcomes

Evaluated the model with:

Confusion Matrix

Accuracy Score

Visualized the non-linear decision boundary

📈 Key Insight

The RBF Kernel projects the data into a higher dimension, enabling the model to draw complex curves as boundaries.

Kernel SVM performs better than Linear SVM and Logistic Regression when classes are not linearly separable.

The decision boundary is smooth and fits the dataset’s structure well.

Scaling the features significantly enhances model performance.

🧪 Outputs

Confusion matrix

Model accuracy

Predicted values

Non-linear classification region visualization

🚀 Conclusion

Kernel SVM is a powerful classification method that handles complex, curved decision boundaries very effectively. On this dataset, it offers a more flexible and accurate prediction model than simple linear classifiers.
