# Titanic Survival Prediction (Machine Learning Project)

## Project Overview
This project applies machine learning techniques to predict whether a passenger survived the Titanic disaster. It demonstrates a complete end-to-end ML workflow including data preprocessing, model training, and evaluation.

---

## Problem Statement
Given passenger details such as age, gender, ticket class, and fare, the goal is to predict survival outcomes using a classification model.

---

## Workflow

### 1. Data Understanding
- Loaded Titanic dataset
- Explored missing values and feature distributions

### 2. Data Preprocessing
- Handled missing values (age, embarked, etc.)
- Encoded categorical variables (Sex, Embarked)
- Selected relevant features for modeling

### 3. Model Building
- Applied Logistic Regression as baseline classification model
- Split data into training and testing sets

### 4. Model Evaluation
- Evaluated using accuracy score
- Confusion matrix used to analyze predictions

---

## Results

The Logistic Regression model achieved approximately **81% accuracy** on the test dataset.

### Key Insights:
- Passenger gender was the strongest factor influencing survival.
- Passenger class (Pclass) had a significant impact on survival probability.
- The model provides a strong baseline for classification tasks on this dataset.

### Evaluation Metrics:
- Accuracy Score: ~0.81
- Confusion Matrix used for performance evaluation

---

## Visualizations
The project includes visual analysis such as:
- Survival distribution
- Survival by gender
- Survival by passenger class
- Confusion matrix heatmap

(All visualizations are available in the `images/` folder)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure

```text
Titanic-Survival-Prediction/
│
├── notebook.ipynb
├── images/
│   ├── confusion_matrix.png
│   ├── survival_by_gender.png
│   └── survival_count.png
└── README.md
 ``` 
---

## Author
Dua Zahra  
LinkedIn: https://www.linkedin.com/in/dua-zahra-ai/  
Email: duazahrazahra344@gmail.com  

---


