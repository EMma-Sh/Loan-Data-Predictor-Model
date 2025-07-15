# 🏦 Loan Approval Prediction System

An end-to-end machine learning project that predicts whether a loan application will be approved based on customer details. This solution covers the full pipeline from data cleaning, model training, and saving, to building a real-time prediction interface using Streamlit.


## 🎯 Project Goal

To build a real-world loan approval prediction system that:
- Cleans and preprocesses data
- Trains and evaluates classification models
- Saves the best-performing model
- Provides a user-friendly interface for real-time predictions

## 🧰 Tools & Technologies

- **Python 3**
- **Pandas, NumPy** — Data preprocessing
- **Scikit-learn** — Modeling & evaluation
- **Joblib** — Model persistence
- **Streamlit** — Web interface for predictions
- **Matplotlib, Seaborn** — Visual exploration (optional)

## 📂 Dataset

- **Name**: Loan Prediction Dataset  
- **Source**: [Kaggle – Loan Prediction](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- **Features Include**:
  - Gender, Marital Status, Education, Applicant Income, Credit History, Loan Amount, etc.
- **Target Variable**: `Loan_Status` (Y/N)

## ⚙️ Project Workflow

1. **Data Cleaning**:
   - Handled missing values (mean/mode strategy)
   - Encoded categorical columns (Label Encoding, One-Hot Encoding)

2. **Model Building**:
   - Trained multiple models: Logistic Regression, Decision Tree, Random Forest
   - Evaluated using accuracy and confusion matrix

3. **Model Saving**:
   - Best-performing model saved using `joblib` or `pickle`

4. **Interface Creation**:
   - Built a basic Streamlit interface to input customer data and show predictions


## 📊 Example Metrics

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 0.81     |
| Decision Tree       | 0.78     |
| Random Forest       | 0.84 ✅ (Saved Model) |


## 🖥️ Streamlit App (User Interface)

Users can input:
- Gender, Marital Status, Education
- Income, Loan Amount, Property Area, etc.

And instantly see whether their **loan is likely to be approved** or not based on the trained model.

## 📁 Folder Structure

📦 loan-approval-prediction
┣ 📄 loan_model.ipynb
┣ 📄 loan_data.csv


---

## 🧠 Key Learning Outcomes

- ✔ Real-world **ML pipeline** implementation  
- ✔ Use of **classification algorithms**  
- ✔ Model **persistence and deployment**  
- ✔ Creating a live **prediction system** with a user interface  

## 👨‍💻 Author

**Eman Iqbal**  
Machine Learning & AI Practitioner  
📍 Pakistan  
📧 emmnqb@gmail.com  
🔗 (https://www.linkedin.com/in/emaniqbal)


## 📌 Future Improvements

- Add model explainability using SHAP or LIME  
- Deploy the Streamlit app on **Streamlit Cloud or Render**  
- Integrate with email alert or database storage for loan officers  
- Add more models (e.g., XGBoost) for comparison


## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
