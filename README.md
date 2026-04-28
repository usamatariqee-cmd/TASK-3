# TASK-3
Heart Disease Prediction 
Objective: 
Build a model to predict whether a person is at risk of heart disease based on their health data.


## 📌 Project Overview
This project focuses on predicting whether a person is at risk of **heart disease** using machine learning techniques. The dataset was analyzed, cleaned, visualized, and used to train a predictive model.

The goal is to identify patterns in patient health data and build a classification model that can accurately predict heart disease risk.

---

## 🎯 Objective
Build a machine learning model to:

- Analyze patient health records
- Handle missing values
- Perform exploratory data analysis (EDA)
- Visualize relationships between features
- Train a classification model
- Evaluate model performance
- Identify important features affecting prediction

---

## 📂 Dataset
The project uses a **Heart Disease Dataset** containing medical attributes such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Number of major vessels (`ca`)
- Thalassemia (`thal`)
- Target (Heart Disease: Yes / No)

---

## 🛠 Technologies Used

### Programming Language
- Python

### Libraries
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Mlxtend

---

## 📊 Exploratory Data Analysis (EDA)
The following analysis was performed:

✔ Dataset shape and structure  
✔ Statistical summary  
✔ Missing value detection  
✔ Feature distributions  
✔ Relationship between input features  
✔ Input vs output analysis  
✔ Outlier detection using boxplots  
✔ PCA visualization for dimensionality reduction  

---

## 🔧 Data Preprocessing
Preprocessing steps included:

- Created copy of original dataset
- Identified missing values in:
  - `ca`
  - `thal`
- Replaced missing values with column mean
- Verified cleaned dataset
- Compared before/after distributions

---

## 🤖 Model Training
### Algorithm Used:
**Logistic Regression**

### Train-Test Split:
- Training set: 80%
- Testing set: 20%

---

## 📈 Model Evaluation
Model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Decision Boundary Visualization

---

## 🔍 Feature Importance
Logistic Regression coefficients were analyzed to determine which medical features have the strongest impact on heart disease prediction.

This helps identify:

- Most influential risk factors
- Positive/negative correlation with disease
- Clinical significance of features

---

## 📁 Project Structure
```
├── TASK-3.ipynb          # Jupyter Notebook
├── Task-3.docx           # Project Documentation
├── heart_disease.csv     # Dataset
└── README.md             # Project Readme
```

---

## 🚀 How to Run

### 1. Clone Repository
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn mlxtend
```

### 3. Run Notebook
```bash
jupyter notebook
```

Open:

`TASK-3.ipynb`

---

## 📌 Results
The Logistic Regression model successfully predicts heart disease risk with strong classification performance.

Key insights:
- Health attributes show clear correlation with heart disease
- Proper preprocessing improves model quality
- Logistic Regression provides interpretable results through feature coefficients


---

## 👨‍💻 Author
USAMA TARIQ
