# Deep Learning Grid Search

Hands-on session on **Deep Learning Grid Search** completed as part of my **Data Science Internship at IIIT Kottayam**.

# Overview
This repository contains the Jupyter Notebook developed during a hands-on session on hyperparameter tuning for deep learning models.

The session demonstrates how **Keras models can be integrated with Scikit-learn** and how **GridSearchCV** can be used to systematically search for suitable hyperparameter combinations.

## Internship Information

* **Institution:** IIIT Kottayam
* **Program:** Data Science Internship / Bootcamp
* **Session Type:** Hands-on Session
* **Topic:** Deep Learning Grid Search

## Objectives

The main objectives of this hands-on session were to understand:

* Keras models with Scikit-learn
* Grid Search using `GridSearchCV`
* Tuning batch size and training epochs
* Tuning learning rate
* Tuning network weight initialization
* Tuning activation functions
* Tuning dropout regularization
* Tuning the number of neurons in hidden layers

## Dataset

The session uses the **Pima Indians Diabetes Dataset**.

The dataset contains diagnostic attributes and a binary `Outcome` variable used for classification.

## Technologies Used

* Python
* Jupyter Notebook / Google Colab
* NumPy
* Pandas
* Scikit-learn
* Keras
* SciKeras
* TensorFlow
* KaggleHub

## Methodology

The hands-on session follows a hyperparameter tuning workflow:

1. Load and prepare the dataset.
2. Standardize the input features.
3. Build a neural network using Keras.
4. Integrate the Keras model with Scikit-learn using SciKeras.
5. Define hyperparameter combinations.
6. Perform Grid Search using `GridSearchCV`.
7. Apply K-Fold cross-validation.
8. Compare the performance of different configurations.
9. Identify the best-performing hyperparameter combination.

## Hyperparameters Explored

The notebook explores different neural-network hyperparameters, including:

* Batch size
* Number of epochs
* Learning rate
* Weight initialization
* Activation function
* Dropout rate
* Number of neurons in hidden layers

## Results

Grid Search is used to identify the best-performing hyperparameter configuration based on cross-validation performance.

The notebook reports the best score and corresponding hyperparameters using `best_score_` and `best_params_`.

## Repository Structure

```text
deep-learning-grid-search/
│
├── Deep_Learning_Grid_Search.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

### Option 1: Google Colab
Open the notebook in Google Colab and run the cells sequentially.
### Option 2: Local Environment
Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/deep-learning-grid-search.git
```

Navigate to the project:

```bash
cd deep-learning-grid-search
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Deep_Learning_Grid_Search.ipynb
```

## Learning Outcome

This hands-on session provided practical experience in deep learning hyperparameter tuning and demonstrated how Grid Search and cross-validation can be used to systematically evaluate different neural-network configurations.

## Author

**Sneha Jose**

Data Science Internship
IIIT Kottayam
