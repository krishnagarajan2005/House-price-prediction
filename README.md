# 🏠 AI-Powered House Price Prediction & Analytics System

## 📌 Project Overview

The **AI-Powered House Price Prediction & Analytics System** is an end-to-end Machine Learning project designed to predict house prices based on important property features.

The project includes the complete Machine Learning pipeline, starting from data collection and preprocessing to model training, evaluation, deployment, and analytics visualization.

The system uses multiple Machine Learning algorithms to analyze house data and select the best-performing model for accurate house price prediction.

---

## 🎯 Project Objectives

* Collect and analyze house price data
* Perform data preprocessing and cleaning
* Handle missing values
* Process numerical and categorical features
* Train multiple Machine Learning models
* Compare model performance
* Select the best-performing model
* Predict house prices using Artificial Intelligence
* Deploy the model using Flask
* Create an analytics dashboard using Streamlit

---

# 📊 Dataset

The dataset used in this project is the **House Prices Dataset**.

The dataset contains information about residential properties, including:

* Overall Quality
* Living Area
* Number of Bedrooms
* Number of Bathrooms
* Year Built
* Garage Capacity
* Basement Area
* Neighborhood
* Property Features
* Sale Price

### Dataset Size

* **Total Records:** 1,460
* **Total Columns:** 81
* **Input Features:** 79
* **Target Variable:** SalePrice

---

# 🧹 Data Preprocessing

The following preprocessing techniques were performed:

* Removed unnecessary ID column
* Identified numerical features
* Identified categorical features
* Handled missing numerical values using Median Imputation
* Handled missing categorical values using Most Frequent Imputation
* Converted categorical features using One-Hot Encoding
* Split the dataset into Training and Testing data

### Train-Test Split

* **Training Data:** 80%
* **Testing Data:** 20%

After preprocessing, the dataset contained **285 processed features**.

---

# 🤖 Machine Learning Models

The following Machine Learning models were trained and compared:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

---

# 📈 Model Performance

| Model                |           MAE |          RMSE |   R² Score |
| -------------------- | ------------: | ------------: | ---------: |
| Linear Regression    |     20,466.13 |     31,294.99 |     0.8723 |
| Decision Tree        |     26,452.03 |     41,191.30 |     0.7788 |
| Random Forest        |     17,386.11 |     28,495.23 |     0.8941 |
| 🏆 Gradient Boosting | **16,946.24** | **27,667.91** | **0.9002** |

## 🏆 Best Model

The **Gradient Boosting Regressor** achieved the best performance.

### Performance

* **MAE:** 16,946.24
* **RMSE:** 27,667.91
* **R² Score:** 0.9002

The model explains approximately **90% of the variation in house prices** on the test dataset.

---

# 🌐 Web Application

A user-friendly House Price Prediction website was developed using **Flask**.

Users can enter the following property details:

* Overall Quality
* Living Area
* Number of Bathrooms
* Number of Bedrooms
* Year Built
* Garage Capacity
* Basement Area

The trained AI model then predicts the estimated house price.

---

# 📊 Analytics Dashboard

An interactive analytics dashboard was created using **Streamlit**.

The dashboard includes:

* Dataset Overview
* House Price Statistics
* House Price Distribution
* Feature Analysis
* Model Performance Comparison
* Interactive Visualizations

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Flask
* Streamlit
* Joblib
* HTML
* CSS
* Git
* GitHub

---

# 🏗️ Project Architecture

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Machine Learning Models
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Save Trained Model
   ↓
Flask Web Application
   ↓
Streamlit Analytics Dashboard
```

---

# 📁 Project Structure

```text
House-Price-Prediction/
│
├── app/
│   ├── app.py
│   ├── templates/
│   │   └── index.html
│   └── static/
│       └── style.css
│
├── dashboard/
│   └── dashboard.py
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── data_description.txt
│   └── sample_submission.csv
│
├── models/
│   ├── house_price_model.pkl
│   └── house_price_web_model.pkl
│
├── src/
│   ├── explore_data.py
│   ├── preprocess.py
│   ├── train_model.py
│   ├── save_model.py
│   └── train_web_model.py
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone <your-repository-url>
```

## Navigate to the Project

```bash
cd House-Price-Prediction
```

## Create a Virtual Environment

```bash
python -m venv venv
```

## Activate the Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

## Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Flask Application

```bash
python app/app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

# 📊 Run the Streamlit Dashboard

```bash
streamlit run dashboard/dashboard.py
```

---

# 🔮 Future Improvements

* Add more advanced Machine Learning models
* Implement XGBoost
* Add Deep Learning models
* Improve feature engineering
* Add real-time prediction analytics
* Deploy the application to cloud platforms
* Improve the user interface
* Add location-based house price prediction

---

# 👨‍💻 Author

**Krishnaveni T N**

UI/UX developer | Full stack developer

---

⭐ If you like this project, feel free to star the repository!
