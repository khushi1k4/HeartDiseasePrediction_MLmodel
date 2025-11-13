# 🛡️ Heart Disease_Prediction Model

A machine learning project to predict the presence of heart disease based on clinical and physiological health parameters.
It helps in early diagnosis, risk identification, and efficient medical decision-making.

---
## 🎯 Objective

To build a predictive ML model that determines whether a person is likely to have heart disease using features like age, cholesterol level, blood pressure, chest pain type, heart rate, and more.

### For Doctors & Healthcare Teams

- Assess heart disease risk quickly

- Support clinical decision-making

- Identify high-risk patients for early treatment

- Prioritize preventive care in critical cases

### For Individuals

- Understand personal risk based on health metrics

- Learn which factors affect heart-related problems

- Encourage lifestyle changes (BMI, BP, exercise, etc.)

### For Healthcare Systems

- Predict population-level heart disease trends

- Enable better planning of medical resources

- Reduce emergency risks through early detection

---
## 🌟 Attributes in this Model

| Attribute            | Description               | Effect                                          |
| -------------------- | ------------------------- | ----------------------------------------------- |
| Age                  | Age of the person         | Older age → higher risk                         |
| Sex                  | Male/Female               | Males have slightly higher risk                 |
| Chest Pain Type (cp) | 4 categories of pain      | Certain types strongly indicate disease         |
| Trestbps             | Resting blood pressure    | Higher BP → potential heart issues              |
| Chol                 | Serum cholesterol         | High levels increase risk                       |
| Fbs                  | Fasting blood sugar       | High sugar → heart complications                |
| Restecg              | Resting ECG results       | Abnormal ECG → higher risk                      |
| Thalach              | Maximum heart rate        | Lower heart rate → higher risk                  |
| Exang                | Exercise-induced angina   | Positive angina → higher chance of disease      |
| Oldpeak              | ST depression             | Higher values show abnormal heart stress        |
| Slope                | Slope of peak exercise ST | Indicates heart performance                     |
| Ca                   | Number of major vessels   | More vessels blocked → higher risk              |
| Thal                 | Thalassemia test result   | Abnormal result → high correlation with disease |

---

## 📈 Project Workflow
```bash
├──Data Loading
├── Data Cleaning and Preprocessing
├── Exploratory Data Analysis (EDA)
├── Feature Selection
├── Train–Test Split
├── Model Training (Logistic Regression)
├── Model Evaluation (Accuracy, ROC Curve, Confusion Matrix)
├── Prediction on New Patient Data
└── Future Suggestions and Improvements

```

## ⚙️ Tools & Libraries

- Python

- NumPy

- Pandas

- Matplotlib

- Scikit-learn

- Jupyter Notebook / VS Code

  
## 📉 Model Evaluation Metrics

1. Accuracy Score → % of correct predictions

2. Confusion Matrix → TP, TN, FP, FN

3. Precision & Recall → critical for medical domain

4. ROC–AUC Score → how well the model separates classes

Higher values indicate better performance in identifying at-risk patients


## 🧠 Why Logistic Regression?

- Ideal for binary classification (disease/no disease)

- Simple, interpretable, and medically explainable

- Lightweight and performs well on structured datasets

- Provides clear probability output

- Strong baseline before using advanced models

## 🔍 Key Insights

- Chest pain type is one of the strongest indicators

- Maximum heart rate (thalach) strongly correlates with target

- Higher oldpeak values show abnormal stress behavior

- Males show slightly higher cases than females

- Cholesterol and BP vary but are not the strongest predictors

---
### 👩‍💻 Author

Khushi Goyal

Machine Learning & Web Development Enthusiast
