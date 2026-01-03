# ml_pipeline_project

# Project Goal

This project demonstrates the basic concepts of Machine Learning using scikit-learn.

The goal is to showcase a complete and practical ML workflow, including:
- data loading
- preprocessing
- model training
- model evaluation

This project is intended for educational purposes.

# Key Concepts Demonstrated

The project covers the following ML fundamentals:
- Supervised Learning (Classification)
- Train-Test Split
- Data Preprocessing
  - feature scaling

Model Evaluation Metrics
- Accuracy
- F1-score
- Classification Report
Feature Importance and Visualization

# Technologies Used
- Python 3.x
- scikit-learn – machine learning models and evaluation metrics
- pandas / numpy – data handling and preprocessing
- matplotlib / seaborn – result visualization (optional)

# Project Structure
ml_pipeline_project/
/ ml_pipeline_project.py     # Script containing the ML pipeline
/ README.md          # Project documentation
/ requirements.txt   # Project dependencies

# Dataset
The project uses the built-in Iris dataset from scikit-learn.
- Number of samples: 150
- Number of features: 4
- Number of classes: 3

# Machine Learning Pipeline
Data Loading
The dataset is loaded and split into:
X – feature matrix
y – target variable

Data Preprocessing
- Numerical feature scaling using StandardScaler

Train-Test Split
- Data is split into training and testing sets (80% / 20%)

Machine Learning Model
- RandomForestClassifier
- Model training on the training set
- Predictions on the test set

Model Evaluation
The following metrics are used:
- Accuracy
- F1-score
- Classification Report

Visualization 
- Feature importance visualization using feature_importances_

# How to Run the Project

Clone the repository:

git clone (https://github.com/Vladyslava14/ml_pipeline_project.git)
cd ml-pipeline-project

Install dependencies:

pip install -r requirements.txt


# Run the script:

python ml_pipeline_project.py

# Results

The model achieves high classification accuracy on the test set, demonstrating that classical machine learning algorithms can perform very well on structured datasets.
