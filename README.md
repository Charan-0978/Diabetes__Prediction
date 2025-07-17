# 🩺 Diabetes Prediction using PIMA Dataset

This project is a machine learning pipeline that predicts whether a person has diabetes using the **PIMA Indian Diabetes dataset**. The pipeline includes data preprocessing, exploratory data analysis (EDA), model training with Logistic Regression, evaluation, and a user-friendly web interface built using **Streamlit**.

---

## 📁 Project Structure

```
Diabetes_prediction/
│
├── diabetes.csv                 # Dataset
├── Diabetes_Prediction.ipynb    # Jupyter notebook with full workflow
├── app.py                       # Streamlit app
├── requirements.txt             # Required libraries
└── README.md                    # Project documentation
```

---

## 📌 Features

- ✅ Cleaned and preprocessed dataset
- 📊 Detailed EDA with visualizations
- 🤖 Model training using **Logistic Regression**
- 🧪 Model evaluation with accuracy and confusion matrix
- 🌐 Streamlit web app for interactive prediction

---

## 🧪 Dataset Info

- **Source**: PIMA Indian Diabetes Dataset
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**: Outcome (0 = No diabetes, 1 = Diabetes)

---

## 🚀 How to Run the Project

### 🔧 1. Clone the repository

```bash
git clone https://github.com/Charan-0978/Diabetes_prediction.git
cd Diabetes_prediction
```

### 📦 2. Install dependencies

Make sure you have Python 3.7 or higher. Then install the required packages:

```bash
pip install -r requirements.txt
```

### 💻 3. Run the Streamlit App

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 📷 App Preview

> 📌 _Add screenshots of your Streamlit interface here for better visualization._

---

## 📈 Model Performance

- Logistic Regression Accuracy: ~78% (based on train-test split)
- Evaluation includes:
  - Confusion Matrix
  - Classification Report
  - Accuracy Score

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Streamlit

---

## 🙌 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ✉️ Contact

For any questions or suggestions, reach out at:  
📧 muppidicharan019@gmail.com
