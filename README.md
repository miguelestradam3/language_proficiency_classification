# 📚 Student English Language Proficiency Prediction using Logistic Regression

This project demonstrates how to build a **Logistic Regression** model using **Scikit-learn** to predict a student's **English language proficiency** based on academic and demographic features. The notebook follows a complete machine learning workflow, including exploratory data analysis (EDA), data preprocessing, feature scaling, model training, and performance evaluation.

The project illustrates how supervised machine learning can be applied in the education domain to classify student language proficiency levels.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Correlation analysis
- Data visualization with Seaborn
- Feature selection
- Train/Test split
- Feature scaling using `StandardScaler`
- Logistic Regression classifier
- Prediction on unseen data
- Classification metrics
- Regression metrics for model evaluation

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```


---

## 📊 Dataset

The notebook uses the **English Learning Dataset**, which contains student-related information used to predict English language proficiency.

The dataset includes multiple academic and personal attributes that may influence language performance.

### Target Variable

- **English Language Proficiency**

The objective is to classify or predict the proficiency level of a student based on the available features.

---

## 🔍 Exploratory Data Analysis

The notebook performs several exploratory analysis tasks, including:

- Dataset inspection
- Statistical summaries
- Correlation analysis
- Heatmap visualization
- Feature relationship exploration

These visualizations help identify the variables that contribute most to predicting language proficiency.

---

## ⚙️ Data Preprocessing

Before training the model, the notebook performs several preprocessing steps:

- Feature selection
- Train/Test split
- Feature scaling using **StandardScaler**
- Preparation of training and testing datasets

Scaling ensures that all numerical features contribute equally during model training.

---

## 🤖 Machine Learning Model

The project uses a **Logistic Regression** classifier from **Scikit-learn**.

Logistic Regression is a widely used supervised learning algorithm for classification problems and serves as a strong baseline model for predictive analytics.

---

## 📈 Model Evaluation

The notebook evaluates the trained model using several metrics, including:

### Classification Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

### Additional Metrics

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

These metrics provide insight into the predictive performance of the model.

---

## 🚀 Getting Started


### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Explore educational datasets
- Visualize feature relationships
- Prepare data for machine learning
- Standardize numerical features
- Train a Logistic Regression classifier
- Evaluate classification models using multiple performance metrics
- Apply machine learning techniques to educational data
