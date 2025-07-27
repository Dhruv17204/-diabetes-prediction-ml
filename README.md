# 🩺 Diabetes Prediction Using Machine Learning

## 🔍 Overview
This project uses machine learning to predict whether a patient is likely to have diabetes, based on health data such as glucose level, BMI, and blood pressure. It utilizes a supervised classification approach using the Logistic Regression model.

## 🧠 Problem Statement
Early prediction of diabetes can help in timely treatment and management of the disease. This model aims to classify patients as diabetic or not based on their medical parameters.

## 📁 Dataset
- **Source**: [Pima Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Attributes**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = Non-diabetic, 1 = Diabetic)

## ⚙️ Tech Stack
- Python 3.8+
- Pandas, NumPy – Data preprocessing
- Scikit-learn – Logistic Regression, model evaluation
- Matplotlib, Seaborn – Visualizations
- Jupyter Notebook – Development environment

## 🔄 Workflow
1. Load dataset
2. Clean and preprocess data
3. Split into training and testing sets
4. Train Logistic Regression model
5. Evaluate with accuracy score & confusion matrix

## 📊 Results
- **Model Used**: Logistic Regression
- **Accuracy Achieved**: ~77%
- **Evaluation**: Confusion matrix, classification report

## 🧪 How to Run
```bash
# Clone the repo
git clone https://github.com/Dhruv17204/Diabetes-Predection-Model-based-on-ML.git
cd Diabetes-Predection-Model-based-on-ML

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook "Diabetes Prediction.ipynb"
```

## 💡 Future Improvements
- Try advanced models like Random Forest, XGBoost
- Use SMOTE for imbalance handling
- Add ROC-AUC analysis

## 👨‍💻 Author
**Dhruv Manoj Patil**  
📧 dhruvpatil1724@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/dhruv-patil) | [GitHub](https://github.com/Dhruv17204)
