Customer Churn Prediction using Machine Learning

Overview

Customer churn is a major challenge for subscription-based businesses such as telecom companies. Predicting which customers are likely to leave helps businesses improve customer retention through targeted interventions.

This project builds a machine learning model to predict customer churn using customer demographic, account, and service-related information. It demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

---

Objectives

* Clean and preprocess customer data.
* Perform Exploratory Data Analysis (EDA).
* Train and compare multiple machine learning models.
* Evaluate model performance using classification metrics.
* Save the best-performing model for future predictions.

---

Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Feature encoding and scaling
* Multiple classification algorithms
* Model evaluation and comparison
* Save and load trained models
* Predict customer churn for new data

---

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook
* Git & GitHub

---

Project Structure

```text
customer-churn-prediction/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   └── predict.py
│
├── models/
│   └── model.pkl
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

Dataset

The dataset contains customer information such as:

* Customer demographics
* Contract details
* Internet services
* Payment methods
* Monthly charges
* Total charges
* Customer churn status

The target variable is **Churn**, which indicates whether a customer has left the service.

---

Machine Learning Models

The following classification algorithms can be used and compared:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (Optional)

---

Model Evaluation

Performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score (Optional)

---

Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Navigate to the project directory:

```bash
cd customer-churn-prediction
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

Usage

Train the model:

```bash
python src/train.py
```

Run predictions:

```bash
python src/predict.py
```

---

## 📷 Results

The project includes visualizations such as:

* Customer churn distribution
* Correlation heatmap
* Feature importance
* Confusion matrix
* Model performance comparison

---

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Feature selection
* Deploy the model using Flask or FastAPI
* Build a Streamlit web application
* Docker support
* Unit testing and CI/CD integration

---

## 📚 Learning Outcomes

This project demonstrates practical experience with:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine learning model development
* Model evaluation
* Model persistence using Joblib
* Git and GitHub project management

---

Contributing

Contributions are welcome. Feel free to fork the repository, create a feature branch, and submit a pull request.

---

License

This project is licensed under the MIT License.

---

Author

Abishek S

If you found this project helpful, please consider giving it a ⭐ on GitHub.
