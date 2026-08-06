# ❤️ Heart Disease Prediction Using Machine Learning

## 📖 About
This project demonstrates an end-to-end machine learning workflow for predicting heart disease using classification algorithms.

The project includes data exploration, preprocessing, feature scaling, model training, evaluation, and comparison of multiple machine learning models to identify the most suitable approach.

## 🚀 Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset
The dataset contains clinical information from patients and is used to perform binary classification for predicting the presence of heart disease.

The dataset is included in this repository.

## 📊 Project Workflow
- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Model Training:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Decision Tree
- Model Evaluation
- Model Comparison
- Final Model Selection

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Logistic Regression | 78.69% | 76.32% | 87.88% | 81.69% |
| KNN | 80.33% | 76.92% | 90.91% | 83.33% |
| SVM | 83.61% | 79.49% | 93.94% | 86.11% |
| Decision Tree | 83.61% | 78.05% | 96.97% | 86.49% |

## 📊 Results Visualization

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)


### Model Comparison

![Model Comparison](images/models_comparison.png)


### Decision Tree Visualization

![Decision Tree](images/decision_tree.png)

## 🏆 Final Model Selection
Decision Tree was selected as the final model because it achieved the highest Recall score (96.97%).

In medical prediction tasks, Recall is an important metric because reducing false negatives helps minimize the risk of missing potential positive cases.

## 👨‍💻 Author
Mehdi Ferdosi

Computer Science Student | Machine Learning Enthusiast

GitHub: https://github.com/mehdifr24
