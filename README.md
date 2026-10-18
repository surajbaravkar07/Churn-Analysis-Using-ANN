# 📊 Customer Churn Prediction Using Artificial Neural Network (ANN)

## 📌 Project Overview

Customer churn refers to customers who stop using a company's products or services. Predicting customer churn helps businesses identify customers who are likely to leave and take preventive actions to improve customer retention.

This project uses an **Artificial Neural Network (ANN)** to predict customer churn based on customer information and account-related features. It also includes a web application for making predictions.

## 🎯 Objectives

- Analyze customer data to understand churn patterns.
- Preprocess data using encoding and feature scaling.
- Build and train an Artificial Neural Network.
- Predict whether a customer is likely to leave the company.
- Provide a simple interface for making predictions.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning:** TensorFlow / Keras
- **Data Analysis:** Pandas, NumPy
- **Machine Learning Utilities:** Scikit-learn
- **Web Framework:** Flask
- **Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook, VS Code

## 📂 Project Structure

```text
ANN/
├── app.py
├── Churn_Modelling.csv
├── experiements.ipynb
├── predict.ipynb
├── model.h5
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── scaler.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/surajbaravkar07/Churn-Analysis-Using-ANN.git
cd Churn-Analysis-Using-ANN
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

If the application starts a local Flask server, open the local URL displayed in your terminal, commonly `http://127.0.0.1:5000`.

## 🧠 Model Workflow

1. **Data Collection:** Load the customer churn dataset.
2. **Data Preprocessing:** Prepare the data and handle categorical features.
3. **Encoding:** Encode categorical variables using the saved encoders.
4. **Feature Scaling:** Scale input features using the saved scaler.
5. **Model Training:** Train an ANN to learn customer churn patterns.
6. **Prediction:** Use the trained model to predict customer churn.
7. **Deployment:** Use the web application to provide predictions from customer inputs.

## 📦 Saved Model Artifacts

| File | Purpose |
|---|---|
| `model.h5` | Saved trained ANN model |
| `label_encoder_gender.pkl` | Saved gender label encoder |
| `onehot_encoder_geo.pkl` | Saved geographical feature encoder |
| `scaler.pkl` | Saved feature scaler |

## 📊 Dataset

The project uses `Churn_Modelling.csv`, which contains customer information and a target variable indicating whether a customer exited the company.

The dataset is used for preprocessing, model development, and churn prediction.

## 🚀 Applications

- Customer retention analysis
- Identification of customers at risk of churn
- Data-driven customer relationship management
- Supporting business decisions through predictive analytics

## 🔮 Future Improvements

- Improve model performance through hyperparameter tuning.
- Add model evaluation metrics and visualizations.
- Deploy the application to a cloud platform.
- Enhance the user interface and prediction explanations.
- Integrate real-time customer data.

## 👨‍💻 Author

**Suraj Baravkar**

GitHub: [@surajbaravkar07](https://github.com/surajbaravkar07)

---

⭐ If you find this project useful, consider giving the repository a star.
