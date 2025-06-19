# Logistic Regression Advanced Case Study

This project is part of the Springboard Data Science Career Track and focuses on advanced applications of logistic regression. The dataset involves predicting heart disease based on various clinical attributes.

## 📁 Project Structure

- data/heart.xlsx – The raw dataset
- notebooks/Logistic_Regression_Advanced_Case_Study.ipynb – Main notebook with analysis and models
- scripts/ – Python scripts for Checkup Exercises I–IV
- requirements.txt – Required Python packages
- README.md – Project overview and instructions

## 🧠 Key Concepts

- Logistic Regression modeling
- Manual cross-validation using KFold
- Hyperparameter tuning (C values)
- Hold-out test set evaluation
- Automated tuning with GridSearchCV

## ✅ Setup Instructions

1. Clone the repository:
   git clone https://github.com/mesfin-k/logistic-regression-case-study.git
   cd logistic-regression-case-study

2. (Optional) Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Open the notebook:
   jupyter notebook notebooks/Logistic_Regression_Advanced_Case_Study.ipynb

## 🔍 Results Summary

- Best C (manual tuning): C=1 with CV score ≈ 0.8266
- Best C (GridSearchCV): C=1 with CV score ≈ 0.8500
- Test Accuracy: Evaluated on hold-out data

## 📊 Dataset

- File: heart.xlsx
- Task: Predicting heart disease (HeartDisease column)
- Features: Age, RestingBP, Cholesterol, MaxHR, Oldpeak, etc.

## 👤 Author

Mesfin Kebede  
📧 mesfin.k.kebede@gmail.com  
🔗 GitHub: https://github.com/mesfin-k

## 📄 License

This project is for educational purposes only and developed as part of Springboard’s Data Science Career Track.
# logistic-regression-case-study
