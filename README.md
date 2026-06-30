# 🚢 Titanic Survival Prediction using Machine Learning

A Machine Learning project that predicts whether a passenger survived the Titanic disaster using classification algorithms. The project includes data preprocessing, feature engineering, model training, and performance evaluation using multiple machine learning models.

---

## 📌 Project Overview

The Titanic dataset is one of the most popular beginner datasets for supervised machine learning. This project demonstrates the complete ML workflow:

- Data Loading
- Data Cleaning
- Missing Value Handling
- Feature Encoding
- Train-Test Split
- Model Training
- Performance Evaluation
- Model Comparison

---

## 📊 Dataset

**Source:** Seaborn Titanic Dataset

The dataset contains passenger information such as:

- Passenger Class
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Port of Embarkation
- Survival Status (Target)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🔄 Machine Learning Workflow

### 1. Import Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

### 2. Load Dataset

The Titanic dataset is loaded using Seaborn.

```python
df = sns.load_dataset("titanic")
```

---

### 3. Data Preprocessing

The following preprocessing steps are performed:

- Remove unnecessary columns
- Handle missing values
- Fill missing Age values with the mean
- Remove rows with missing Embarked values
- Convert categorical variables into numerical values using Label Encoding

---

### 4. Feature Selection

Features used for prediction include:

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

Target Variable:

- Survived

---

### 5. Train-Test Split

Dataset is divided into training and testing sets using:

- 67% Training Data
- 33% Testing Data

---

## 🤖 Machine Learning Models

### Logistic Regression

Used as the baseline classification model.

### K-Nearest Neighbors (KNN)

Features are standardized before training.

### Gaussian Naive Bayes

A probabilistic classifier based on Bayes' theorem.

---

## 📈 Model Evaluation

Each model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
```

### 2. Navigate to Project

```bash
cd Titanic-Survival-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Titanic_Survival_Prediction.ipynb
```

Run all cells.

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Install all packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
```

---

## 📊 Evaluation Metrics

The project compares different machine learning models based on:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

This helps determine which algorithm performs best for the Titanic survival prediction task.

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier
- Cross Validation
- Feature Engineering
- Model Deployment using Streamlit or Flask

---

## 🎯 Learning Outcomes

This project demonstrates:

- Data Cleaning
- Missing Value Handling
- Label Encoding
- Feature Selection
- Data Standardization
- Supervised Machine Learning
- Classification Algorithms
- Model Evaluation
- Performance Comparison

---

## 👨‍💻 Author

**Jatin Jangid**

**B.Tech – Artificial Intelligence & Data Science**

**Skills:** Python, Machine Learning, Data Analysis, Scikit-learn, SQL, Generative AI

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub and feel free to contribute or suggest improvements!

---

## 📄 License

This project is created for educational and learning purposes.