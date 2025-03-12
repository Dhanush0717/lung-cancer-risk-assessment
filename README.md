# 🫁 Lung Cancer Risk Assessment Model

## 📌 Overview
This project implements a **Lung Cancer Risk Assessment Model** using **machine learning algorithms** to predict the likelihood of lung cancer based on survey data. The model utilizes **SVM, Random Forest, and Decision Tree classifiers** for prediction and analysis.

## 📊 Dataset
The dataset consists of survey responses with multiple features such as **age, smoking habits, chronic disease history, and more** to assess lung cancer risk. 

### 📌 Features:
- 🧑‍⚕️ **GENDER** (0 = Male, 1 = Female)
- 🎂 **AGE** (Numerical)
- 🚬 **SMOKING** (1 = Yes, 0 = No)
- 🟡 **YELLOW_FINGERS** (1 = Yes, 0 = No)
- 😰 **ANXIETY** (1 = Yes, 0 = No)
- 👫 **PEER_PRESSURE** (1 = Yes, 0 = No)
- 🏥 **CHRONIC DISEASE** (1 = Yes, 0 = No)
- 😴 **FATIGUE** (1 = Yes, 0 = No)
- 🤧 **ALLERGY** (1 = Yes, 0 = No)
- 😤 **WHEEZING** (1 = Yes, 0 = No)
- 🍷 **ALCOHOL CONSUMPTION** (1 = Yes, 0 = No)
- 🤧 **COUGHING** (1 = Yes, 0 = No)
- 😮‍💨 **SHORTNESS OF BREATH** (1 = Yes, 0 = No)
- 😖 **SWALLOWING DIFFICULTY** (1 = Yes, 0 = No)
- 💔 **CHEST PAIN** (1 = Yes, 0 = No)
- 🫁 **LUNG_CANCER** (Target Variable: 1 = Yes, 0 = No)

## ⚙️ Installation & Requirements
To run this project, install the required dependencies using the following command:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 🚀 Usage
1. **📥 Load the dataset**
   ```python
   df = pd.read_csv("survey_lung_cancer.csv")
   ```
2. **🔍 Preprocess Data** (handling missing values, encoding categorical data, and removing duplicates).
3. **📊 Exploratory Data Analysis (EDA)**
   - Checking distributions
   - Correlation heatmaps
   - Feature importance analysis
4. **🤖 Train ML Models**
   ```python
   from sklearn.svm import SVC
   svc = SVC(kernel='linear')
   svc.fit(X_train, y_train)
   ```
5. **📈 Evaluate Models**
   ```python
   from sklearn.metrics import accuracy_score
   acc = accuracy_score(y_test, y_pred)
   print(f"Model Accuracy: {acc}")
   ```

## 📊 Model Performance
The following models were trained:
- **🤖 Support Vector Machine (SVM)**
- **🌲 Random Forest Classifier**
- **🌳 Decision Tree Classifier**

### 🎯 Accuracy Scores:
| Model               | Accuracy |
|---------------------|----------|
| 🌲 Random Forest      |  *xx%*    |
| 🤖 Support Vector Machine | *xx%*  |
| 🌳 Decision Tree      |  *xx%*    |

## 📈 Visualizations
- 📊 Distribution plots for each feature
- 🔥 Correlation heatmaps
- 📉 Model performance comparison

## 🔮 Future Improvements
- 🏥 Collect more diverse data for better generalization
- 🧠 Implement deep learning models for higher accuracy
- 🌐 Deploy as a web application

## 🌐 Live Demo
Check out the live demo of the Lung Cancer Risk Assessment Model here:
[🔗 Lung Cancer Risk Assessment](https://lungcancerriskassessment.netlify.app/)

## 📜 License
This project is open-source and available under the **MIT License**.

---
### ✍️ Author: [Your Name]
