# Voting Classifier on the Iris Dataset

## Overview
This project demonstrates the implementation of a **Voting Classifier** using multiple machine learning models on the **Iris dataset** to enhance classification accuracy. A Voting Classifier aggregates predictions from multiple classifiers to make a final decision.

## Dataset
The **Iris dataset** consists of 150 samples categorized into three species:
- Setosa
- Versicolor
- Virginica

Each sample includes four features:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

## Models Used
The following machine learning models are combined in the Voting Classifier:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**

The classifier employs two voting strategies:
- **Hard Voting**: Assigns the class label with the most votes.
- **Soft Voting**: Assigns the class label with the highest average predicted probability.

## Installation
Ensure Python is installed along with the necessary libraries. Install dependencies using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
Run the Python script to train and evaluate the model:
```bash
python voting_classifier_iris.py
```

## Evaluation Metrics
The Voting Classifier improves classification accuracy compared to individual models. The following metrics are used for performance evaluation:
- Accuracy
- Precision
- Recall
- Confusion Matrix

## Results
The model is expected to yield a higher accuracy than individual classifiers by leveraging their combined strengths. The final results will be displayed with visualizations and metric scores.

## References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Iris Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

