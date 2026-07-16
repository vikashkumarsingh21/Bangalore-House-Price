# 🏠 Bengaluru House Price Prediction

A Machine Learning project that predicts house prices in Bengaluru based on various property features such as location, total square feet, number of bedrooms, and bathrooms.

This project demonstrates the complete Machine Learning workflow including data cleaning, feature engineering, outlier removal, preprocessing, and model training using Python and Scikit-learn.

---

## 📌 Project Overview

Real estate prices vary significantly depending on multiple factors. The objective of this project is to build a Machine Learning model capable of predicting house prices in Bengaluru using historical housing data.

The project includes:

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Outlier Detection & Removal
- Data Preprocessing
- Machine Learning Model Training
- House Price Prediction

---

## 📂 Project Structure

```
Bengaluru-House-Price-Prediction/
│
├── Predictor.ipynb              # Complete Jupyter Notebook
├── Bengaluru_House_Data.csv     # Original Dataset
├── Cleaned_data.csv             # Cleaned Dataset
├── README.md
└── requirements.txt
```

---

## 🚀 Features

- Data preprocessing
- Missing value handling
- Feature engineering
- Convert sqft ranges into numeric values
- Remove unwanted columns
- Remove outliers
- One-Hot Encoding
- Train Regression Models
- Predict Bengaluru house prices

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains housing information such as:

- Location
- Size (BHK)
- Total Square Feet
- Bathrooms
- Price

After preprocessing, unnecessary columns are removed and the data is cleaned for Machine Learning.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed unwanted columns
- Filled missing values
- Converted sqft ranges into numerical values
- Created BHK feature
- Calculated Price Per Square Feet
- Removed locations having very few data points
- Removed outliers
- Generated cleaned dataset

---

## 🤖 Machine Learning Models

The following regression algorithms are used:

- Linear Regression
- Lasso Regression
- Ridge Regression

These models are trained to predict house prices based on the cleaned dataset.

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/vikashkumarsingh21/Bangalore-House-Price.git
```

Move into the project folder

```bash
cd YOUR_REPOSITORY
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Predictor.ipynb
```

Run all cells.

---

## ▶️ How to Run

### Step 1

Clone the repository

```bash
git clone https://github.com/vikashkumarsingh21/Bangalore-House-Price.git
```

### Step 2

Go inside the project

```bash
cd YOUR_REPOSITORY
```

### Step 3

Install dependencies

```bash
pip install -r requirements.txt
```

### Step 4

Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5

Open

```
Predictor.ipynb
```

### Step 6

Run every notebook cell from top to bottom.

---

## 📋 Requirements

Create a file named `requirements.txt`

```text
numpy
pandas
scikit-learn
jupyter
matplotlib
```

Install using

```bash
pip install -r requirements.txt
```

---

## 📈 Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
Outlier Removal
   │
   ▼
Data Preprocessing
   │
   ▼
Model Training
   │
   ▼
House Price Prediction
```

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Cross Validation
- Random Forest Regressor
- XGBoost Regressor
- Flask Web Application
- Streamlit Deployment
- Docker Support
- Cloud Deployment

---

## 👨‍💻 Author

**Vikas Kumar Singh**

B.Tech CSE (AI & ML)

Passionate about Artificial Intelligence, Machine Learning, Data Science, and Full Stack Development.

GitHub: https://github.com/vikashkumarsingh21

LinkedIn: https://www.linkedin.com/in/vikas-kumar-0803r/

---

## ⭐ Support

If you found this project useful, don't forget to ⭐ star this repository and share it with others!

Happy Coding 🚀