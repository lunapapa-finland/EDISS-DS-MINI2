# EDISS-DS-MINI2

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18SYY2DlmjwVldnXyh8_hfFkaXFFaQ0Y9?usp=sharing)

## Abstract
This machine learning initiative focuses on the classification task of predicting the final grades for 107 enrolled students in a fully online, nine-week machine learning course. The study, administered via the Moodle learning management system, utilizes students' performance metrics, including mini projects, quizzes, peer reviews, and the final grade. Through essential phases like exploratory data analysis, data preprocessing, feature selection, and algorithm selection, the project consistently yields highly accurate models, surpassing a 77% accuracy threshold.

## 1 Introduction
In the context of digital transformation in education, accurately predicting student performance in online courses becomes crucial for proactive intervention. The project uses a dataset from 107 students, employing a structured workflow for predictive modeling. Key phases include exploratory data analysis (EDA), data preprocessing, and feature selection, streamlining the feature set for subsequent analysis.

## 2 EDA, Data Preprocessing and Feature Selection
### 2.1 Exploratory Data Analysis (EDA)
The initial step involves examining and visualizing the dataset. Highlights include 107 rows, 48 columns, and no missing values or outliers. Various data types are observed, and data characteristics such as quiz and project grades are explored.

### 2.2 Data Preprocessing
Given the dataset's cleanliness, specific preprocessing steps involve removing uniform features and the 'ID' feature.

### 2.3 Feature Selection
Feature selection is performed based on correlation analysis, retaining 18 features and 1 label for the dataset.

## 3 Algorithm Selection
To address the classification problem, various machine learning algorithms are evaluated, including "K-Nearest Neighbors," "Decision Tree," and "Random Forest." Cross-validation is employed for fair comparison, with Decision Tree emerging as the top performer.

## 4 Model Selection and Hyper-parameter Tuning
Three algorithms are selected for model training: K-Nearest Neighbors, Decision Tree, and Random Forest. Hyper-parameter tuning is performed to optimize each model.

### 4.1 K Nearest Neighbours
Hyper-parameter tuning for KNN involves pruning features, optimizing the number of neighbors (K), and thresholding accuracy scores.

### 4.2 Decision Tree
Grid search is applied to identify optimal hyper-parameters for the Decision Tree. The model's overfitting tendencies are visualized and feature importance is analyzed.

### 4.3 Random Forest
Similar to Decision Tree, Random Forest undergoes grid search for optimal hyper-parameters. The ensemble method outperforms Decision Tree, demonstrating higher accuracy.

## 5 Conclusion
### 5.1 Model Comparison
The Decision Tree, KNN, and Random Forest models are compared, highlighting their respective strengths and weaknesses. Decision Tree exhibits overfitting, while KNN and Random Forest achieve better accuracy.

### 5.2 Scientific Bottlenecks
Data inadequacy and limited knowledge in data science present challenges. The grading mechanism's simplicity and potential relationships between learning activities and grades could be explored further with more data.

The project represents a significant learning experience in data science, with an aspiration to gain mastery over a broader array of algorithms and evaluation methods for constructing more robust models in the future.