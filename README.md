# Heart Disease Prediction System

## Project Description

This project is a Machine Learning-based Heart Disease Prediction System that predicts whether a person has heart disease or not based on medical attributes.
It uses a Logistic Regression model trained on a dataset of patient health data.

---

## Features

* Predicts heart disease (Defective / Healthy)
* Uses real medical dataset
* Data preprocessing and analysis included
* Model training and evaluation
* Accuracy calculation (training & test data)
* Custom input prediction system

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

## Dataset Information

The dataset contains medical attributes such as:

* Age
* Sex
* Chest pain type
* Blood pressure
* Cholesterol level
* Heart rate
* And more...

### Target Variable:

* `1` → Defective Heart
* `0` → Healthy Heart

---

## Installation & Setup

### Step 1: Clone Repository

```bash
git clone <your-repo-link>
cd <project-folder>
```

### Step 2: Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### Step 3: Run the Notebook

```bash
jupyter notebook
```

Then open:

```
Heart_Disease_Prediction.ipynb
```

---

## Project Workflow

1. Import dependencies
2. Load dataset (CSV file)
3. Data analysis (info, null values, statistics)
4. Feature & target separation
5. Train-test split
6. Model training using Logistic Regression
7. Model evaluation using accuracy score
8. Prediction system for new input

---

## Model Performance

* Training Accuracy: Good accuracy on training dataset
* Testing Accuracy: Good generalization on unseen data

