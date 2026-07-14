# 💼 Employee Salary Prediction using Machine Learning

## 📌 Project Overview

This project predicts employee salaries using Machine Learning based on various job-related features such as experience level, employment type, job title, salary currency, employee residence, remote work ratio, company location, and company size.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple regression algorithms to identify the best-performing model.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Label Encoding for Categorical Features
- Feature Scaling using StandardScaler
- Multiple Regression Models
- Model Performance Comparison
- Data Visualization
- Salary Prediction

---

## 📂 Dataset

**Dataset:** `ds_salaries.csv`

The dataset contains information about employee salaries in the Data Science industry.

### Features

- work_year
- experience_level
- employment_type
- job_title
- salary
- salary_currency
- salary_in_usd (Target Variable)
- employee_residence
- remote_ratio
- company_location
- company_size

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project performs:

- Dataset inspection
- Missing value checking
- Duplicate removal
- Statistical summary
- Correlation analysis
- Distribution plots
- Salary analysis
- Feature relationship visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Label Encoding for categorical variables
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models Used

The following regression algorithms were implemented and compared:

- Random Forest Regressor
- Linear Regression
- Support Vector Regressor (SVR)
- K-Nearest Neighbors Regressor (KNN)
- XGBoost Regressor
- Decision Tree Regressor

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The performance of all models was compared to determine the most accurate salary prediction model.

---

## 📉 Visualizations

The notebook includes several visualizations such as:

- Salary Distribution
- Correlation Heatmap
- Feature Importance
- Model Performance Comparison
- R² Score Comparison Graph

---

## 📁 Project Structure

```
Employee_Salary_Prediction/
│
├── ds_salaries.csv
├── Employee_Salary_Prediction_Project.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Employee-Salary-Prediction.git
```

Navigate to the project folder:

```bash
cd Employee-Salary-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
scikit-learn
xgboost
jupyter
```

---

## 🎯 Project Workflow

1. Load Dataset
2. Explore Dataset
3. Clean Data
4. Encode Categorical Features
5. Scale Numerical Features
6. Split Data into Training and Testing Sets
7. Train Multiple Machine Learning Models
8. Evaluate Model Performance
9. Compare Models
10. Predict Employee Salary

---

## 📌 Results

- Successfully trained and evaluated multiple regression models.
- Compared model performance using standard evaluation metrics.
- Identified the best-performing model for salary prediction.
- Demonstrated how machine learning can accurately estimate employee salaries based on professional and organizational attributes.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Cross-validation
- Deployment using Streamlit or Flask
- Real-time salary prediction web application
- Feature engineering for improved accuracy

---

## 👨‍💻 Author

**Madiboyina Kalyan**

- B.Tech in Computer Science Engineering
- Python | Machine Learning | Data Analysis | SQL
- Passionate about AI, Data Science, and Software Development

---

## ⭐ If you found this project helpful, consider giving it a Star!
