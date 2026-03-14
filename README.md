# Heart Disease Prediction using Machine Learning

This project is a **Machine Learning-based web application** that predicts the risk of heart disease based on patient medical attributes.
The model is trained using **Logistic Regression** and deployed as an **interactive web application using Streamlit**.

The application allows users to input medical details such as age, cholesterol, blood pressure, and heart rate to receive a prediction of whether heart disease is likely or not.

---

# 🚀 Live Application

Streamlit Deployment:
https://heart-disease-prediction-monisha.streamlit.app

---

# 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can help medical professionals make better decisions and improve patient outcomes.

This project demonstrates a **complete machine learning workflow**, including:

• Data preprocessing and cleaning
• Exploratory Data Analysis (EDA)
• Model training using Logistic Regression
• Model evaluation
• Web application deployment using Streamlit

---

# 📊 Dataset Information

The dataset contains medical attributes related to heart disease.

**Total records:** 228 patients
**Total features:** 14 medical attributes

Important features include:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol Level
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression (Oldpeak)
* Slope of ST Segment
* Number of Major Vessels
* Thalassemia

**Target Variable**

| Value | Meaning               |
| ----- | --------------------- |
| 0     | No Heart Disease      |
| 1     | Heart Disease Present |

---

# 🔎 Exploratory Data Analysis (EDA)

EDA was performed using:

* Pandas
* Matplotlib
* Seaborn

The analysis included:

* Dataset inspection
* Missing value detection
* Duplicate record removal
* Statistical summaries
* Data visualization
* Correlation heatmap

### Key Insights

* Most patients fall between **45–65 years of age**
* Dataset contains **more male patients**
* **Chest pain type** and **maximum heart rate** show strong correlation with heart disease
* **Exercise-induced angina** appears more frequently in patients with heart disease

---

# 🤖 Machine Learning Model

Algorithm Used:

**Logistic Regression**

### Model Training

* Data Split: **80% Training / 20% Testing**
* Feature Scaling: **StandardScaler**
* Evaluation Metrics Used:

  * Accuracy
  * Confusion Matrix
  * Precision
  * Recall
  * F1-score

### Model Performance

Accuracy Achieved:

**84.78%**

Confusion Matrix Results:

| Metric          | Value |
| --------------- | ----- |
| True Negatives  | 13    |
| False Positives | 2     |
| False Negatives | 5     |
| True Positives  | 26    |

The model demonstrates **strong predictive performance for heart disease detection**.

---

# 🌐 Streamlit Web Application

The trained model was deployed using **Streamlit** to create an interactive web interface.

### Features of the Application

* User-friendly medical input form
* Real-time heart disease prediction
* Light and Dark theme support
* Machine learning model integration
* Runs on Streamlit Cloud

Users can enter patient information and instantly receive a prediction.

---

# 🛠️ Technologies Used

Programming Language

* Python

Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Streamlit

Tools

* Google Colab
* VS Code
* GitHub
* Streamlit Cloud

---

# 📂 Project Structure

```
Heart-Disease-Prediction-Streamlit
│
├── app.py
├── heart_model.pkl
├── scaler.pkl
├── requirements.txt
├── HeartClean_Dataset.csv
└── Heart_MLModel.ipynb
```

---

# ⚙️ How to Run the Project Locally

Clone the repository

```
git clone https://github.com/Monisha8-ux/Heart-Disease-Prediction-Streamlit.git
```

Navigate to the project folder

```
cd Heart-Disease-Prediction-Streamlit
```

Install dependencies

```
pip install -r requirements.txt
```

Run the Streamlit app

```
streamlit run app.py
```

Open the browser and visit:

```
http://localhost:8501
```

---

# 📈 Future Improvements

* Use advanced models such as Random Forest or XGBoost
* Add probability-based risk score
* Improve UI with medical dashboards
* Add data visualization inside the web app
* Deploy using Docker or cloud platforms

---

# 👩‍💻 Author

**Monisha Sharma**

Computer Science & Data Science Student
Machine Learning | Data Analysis | AI

GitHub:
https://github.com/Monisha8-ux

---

# ⭐ If you found this project useful, consider giving it a star!
