🚢 Titanic Survival Prediction

Predict the survival of passengers aboard the Titanic using machine learning.
Built with Python, Scikit-learn, and deployed using Streamlit.

📌 Table of Contents

Overview

Dataset

Project Workflow

Technologies Used

Installation

Usage

Results

Future Improvements

License

📖 Overview

The Titanic sank in 1912, taking over 1500 lives.
This project predicts whether a passenger survived based on:

Passenger class

Gender

Age

Family size

Fare paid

Port of embarkation

Live App Screenshot:


📊 Dataset

We use the Kaggle Titanic dataset:


Feature	Description
Survived	0 = No, 1 = Yes
Pclass	Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex	Gender
Age	Passenger age
SibSp	Siblings/spouses aboard
Parch	Parents/children aboard
Fare	Ticket price
Embarked	Port of embarkation
🔄 Project Workflow

Steps:

Data Cleaning – Handle missing values & inconsistent data.

Feature Engineering – Encode categorical variables, create new features.

Exploratory Data Analysis (EDA) – Visualize survival trends.

Model Training – Random Forest Classifier with cross-validation.

Evaluation – Accuracy score & confusion matrix.

Deployment – Streamlit web app.

🛠 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Streamlit

⚙ Installation
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt

🚀 Usage

Run the Streamlit app:

streamlit run titanic_streamlit.py


Then visit:

http://localhost:8501

📈 Results

Feature Importance Plot:


Model Performance:

Accuracy: ~82%

Most important features: Sex, Pclass, Fare, Age

🔮 Future Improvements

Add advanced models like XGBoost & LightGBM.

Deploy to Streamlit Cloud.

Add interactive visualizations.
