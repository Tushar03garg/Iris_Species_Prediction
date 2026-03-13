# Iris Species Prediction using Machine Learning

## Project Overview

This project predicts the **species of iris flowers** using multiple machine learning classification algorithms.
The models are trained on the **Iris dataset**, which contains measurements of flower features.

Three algorithms were implemented and compared:

* Logistic Regression
* Multinomial Naive Bayes
* K-Nearest Neighbors (KNN)

To improve model performance, **GridSearchCV** was used for hyperparameter tuning.

The models were evaluated and compared using **Accuracy, Precision, and Recall scores**.

---

## Dataset

The dataset used is the **Iris dataset**, which contains measurements of iris flowers.

### Features in the Dataset

| Feature       | Description                      |
| ------------- | -------------------------------- |
| SepalLengthCm | Length of the sepal              |
| SepalWidthCm  | Width of the sepal               |
| PetalLengthCm | Length of the petal              |
| PetalWidthCm  | Width of the petal               |
| Species       | Target variable (flower species) |

### Target Classes

The model predicts one of the following species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Python Script

---

## Machine Learning Algorithms Used

### Logistic Regression

A statistical model used for **classification problems**, which predicts the probability of class membership.

### Multinomial Naive Bayes

A probabilistic classifier based on **Bayes theorem**, commonly used for classification tasks.

### K-Nearest Neighbors (KNN)

A non-parametric algorithm that classifies data points based on the **nearest neighbors** in the feature space.

---

## Hyperparameter Tuning

**GridSearchCV** was used to find the best parameters for the models by performing cross-validation and testing multiple parameter combinations.

---

## Model Evaluation

The models were evaluated using the following metrics:

* **Accuracy Score**
* **Precision Score**
* **Recall Score**

These metrics help determine how well each algorithm performs on the classification task.

---

## Model Comparison

The performance of all three algorithms was compared to identify which model performs best on the dataset.

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Feature selection
5. Train-test split
6. Train multiple machine learning models
7. Hyperparameter tuning using GridSearchCV
8. Evaluate models using performance metrics
9. Compare model results

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/iris-species-prediction.git
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

Run the project:

```bash
python iris_classification.py
```

---

## Project Structure

```
iris-species-prediction
│
├── Iris.csv
├── iris_classification.py
├── notebook.ipynb
└── README.md
```

---

## Future Improvements

* Add more classification algorithms (SVM, Decision Tree, Random Forest)
* Improve visualization of model results
* Create a web application for species prediction
* Deploy the model using Flask or Streamlit

---

## Author

Tushar Garg

GitHub: https://github.com/Tushar03garg
