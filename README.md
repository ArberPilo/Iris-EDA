Project Overview
This project focuses on applying different Machine Learning algorithms to the Iris dataset in order to classify flower species based on their features. The goal is to explore, preprocess, and compare multiple models to understand their performance.

Dataset
The dataset used is the famous Iris dataset, which includes:
Sepal length
Sepal width
Petal length
Petal width
Target variable: variety (Setosa, Versicolor, Virginica)

Steps Performed

1. Data Loading

The dataset was loaded using pandas and inspected for structure and basic information.

2. Data Exploration (EDA)
   Checked dataset shape and structure
   Visualized distributions using pairplot and boxplots
   Analyzed correlations using a heatmap
   Detected outliers using IQR method
3. Data Preprocessing
   Handled duplicates and checked for missing values
   Encoded the target variable using Label Encoding
   Split the dataset into training and testing sets
4. Machine Learning Models

The following models were implemented:

Decision Tree
Linear Regression
Logistic Regression
Naive Bayes

5. Model Evaluation

Each model was evaluated using:

Accuracy
Precision
Recall
Confusion Matrix

Results & Comparison
The models were compared based on their performance metrics to identify which algorithm works best for this classification problem.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Conclusion
This project demonstrates how different machine learning models perform on a simple classification dataset and highlights the importance of preprocessing and model evaluation.
