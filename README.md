# 🧠 Brain Stroke Prediction Using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Classification-orange" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Modeling-F7931E?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Project-Healthcare%20AI-red" />
  <img src="https://img.shields.io/badge/Status-Research%20Project-success" />
</p>

## 📌 Project Overview

This project focuses on developing a machine learning-based system to predict the likelihood of brain stroke using demographic, medical, clinical, and lifestyle-related information.

The main objective is to investigate the effectiveness of different supervised machine learning algorithms in identifying potential stroke cases through data-driven predictive modelling.

The project includes data preprocessing, exploratory data analysis (EDA), statistical analysis, machine learning implementation, model comparison, and performance evaluation.

## 🎯 Research Objectives

- 🧬 Investigate demographic, medical, and lifestyle-related factors associated with stroke prediction.
- 📊 Perform exploratory data analysis to understand dataset characteristics and distributions.
- ⚙️ Apply data preprocessing and feature standardisation techniques.
- 🤖 Develop multiple supervised machine learning classification models.
- 📈 Compare model performance using different evaluation metrics.
- 🏆 Identify the best-performing model based on experimental results.

## 📂 Dataset Description

The dataset contains **12,000 records, 16 input features, and 1 target variable**.

### 👤 Demographic Features
- Age
- Gender

### 🏥 Medical History
- Hypertension
- Diabetes
- Heart Disease
- Family History of Stroke

### 🚭 Lifestyle Factors
- Smoking History
- Alcohol Consumption
- Physical Activity

### 🩺 Clinical Measurements
- Cholesterol Level
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Body Mass Index (BMI)
- Glucose Level

### 🧪 Medical Imaging Features
- MRI Scan Results
- CT Scan Results

### 🎯 Target Variable
- `0` – No Stroke
- `1` – Stroke

## 🔍 Exploratory Data Analysis (EDA)

Exploratory data analysis was performed to understand the structure, distribution, and relationships within the dataset.

Key activities included:

- 📋 Dataset inspection and statistical summaries.
- 🔎 Missing-value detection.
- ♻️ Duplicate-record identification.
- 📊 Numerical feature distribution analysis.
- 🔗 Correlation analysis.
- 🧩 Pairplot visualisation.
- 📉 Feature comparison based on the target variable.

These analyses helped establish an understanding of the dataset before developing the machine learning models.

## 🛠️ Data Preprocessing

The following preprocessing activities were performed:

- 🧹 Data cleaning and dataset inspection.
- 🔠 Categorical feature encoding.
- 🎚️ Feature standardisation using `StandardScaler`.
- ✂️ Separation of independent variables and target variable.
- 📦 Training and testing data split (70:30).

## 🤖 Machine Learning Algorithms

Five supervised machine learning classification algorithms were implemented and evaluated.

| No. | Algorithm | Description |
|---|---|---|
| 1️⃣ | Logistic Regression | Baseline classification algorithm |
| 2️⃣ | Random Forest | Ensemble learning using multiple decision trees |
| 3️⃣ | K-Nearest Neighbors (KNN) | Distance-based classification |
| 4️⃣ | Support Vector Machine (SVM) | Margin-based classification |
| 5️⃣ | Gradient Boosting | Sequential ensemble learning |

## 📊 Model Performance Evaluation

The models were evaluated using the following metrics:

- 🎯 Accuracy
- 🔍 Precision
- 📈 Recall
- ⚖️ Weighted F1-score
- 🧮 Confusion Matrix
- 📑 Classification Report

## 🏆 Experimental Results

The following table presents the experimental results obtained from the held-out test dataset.

| Machine Learning Model | Accuracy | Weighted F1-score |
|---|---:|---:|
| Logistic Regression | 85% | 84.55% |
| Random Forest | 93% | 93.03% |
| K-Nearest Neighbors | 80% | 80.15% |
| Support Vector Machine | 85% | 84.70% |
| **Gradient Boosting** | **98%** | **97.54%** |

### 🥇 Best Performing Model: Gradient Boosting

Gradient Boosting achieved the strongest reported performance among the five implemented classification algorithms.

**Key performance indicators:**

- 🎯 Accuracy: Approximately 97.56%
- ⚖️ Weighted F1-score: 97.54%
- 🔍 Class 1 Precision: 96%
- 📈 Class 1 Recall: 100%

### 🧮 Confusion Matrix – Gradient Boosting

| Actual / Predicted | No Stroke (0) | Stroke (1) |
|---|---:|---:|
| No Stroke (0) | 1,418 | 87 |
| Stroke (1) | 1 | 2,094 |

The confusion matrix demonstrates the model's classification performance on the test dataset. Further independent validation is necessary before interpreting these results in a clinical context.

## 💻 Technologies & Tools

| Technology | Application |
|---|---|
| 🐍 Python | Programming language |
| 🐼 Pandas | Data manipulation and analysis |
| 🔢 NumPy | Numerical computing |
| 📊 Matplotlib | Data visualisation |
| 🎨 Seaborn | Statistical visualisation |
| 🤖 Scikit-learn | Machine learning implementation |
| 📓 Jupyter Notebook | Experimental development environment |

## 📁 Project Structure

```text
Brain_Stroke/
│
├── 📓 Brain_Stroke.ipynb
├── 📄 stroke_prediction_data.csv
└── 📘 README.md
```

## 🌟 Key Project Highlights

- 📂 Analysed a dataset containing 12,000 records.
- 🧬 Investigated 16 input features related to healthcare and lifestyle.
- 🔍 Conducted exploratory data analysis and statistical investigation.
- 🤖 Implemented five supervised machine learning algorithms.
- 📊 Compared model performance using multiple evaluation metrics.
- 🏆 Achieved a 97.54% weighted F1-score using Gradient Boosting.
- 🧮 Evaluated classification outcomes using confusion matrices.

## 🚀 Future Improvements

Potential directions for extending this project include:

- 🔧 Hyperparameter optimisation using GridSearchCV and RandomizedSearchCV.
- 🔄 Stratified k-fold cross-validation.
- 🧠 Model explainability using SHAP and feature importance.
- 🏥 Independent validation using real-world clinical datasets.
- 🌐 Development of an interactive prediction application.
- ☁️ Model deployment using Flask or FastAPI.
- 📱 Integration into a healthcare-oriented application prototype.

## ⚠️ Limitations & Disclaimer

This project is intended for educational and research purposes. The reported results represent experimental performance on the available dataset and do not establish clinical validity.

The system is not intended to replace professional medical advice, diagnosis, or treatment. Independent validation using appropriate real-world clinical data is required before any practical healthcare application.

## 👨‍💻 Author

**Roshan Kumar Sah**

🎓 BSc (Hons) Computer Systems Engineering

🔗 **GitHub:** [github.com/roshanksah](https://github.com/roshanksah)

💡 **Research Interests:** Artificial Intelligence, Machine Learning, Healthcare Analytics, Edge Computing, and Internet of Things (IoT).

---

<p align="center">
  🧠 <b>Exploring the Potential of Artificial Intelligence in Healthcare</b>
  <br/>
  <i>Transforming Health Data into Meaningful Predictive Insights.</i>
</p>
