💓 Heart Disease Prediction Using Machine Learning
By Gulam Mohiuddin Kadri
ID: 231003003039


---

📌 Project Overview

This project aims to predict the likelihood of heart disease in a person using Machine Learning techniques.
The system takes several medical input parameters such as age, chest pain type, cholesterol, blood pressure, ECG, etc., and predicts whether the person is at risk of heart disease.

The model used is Logistic Regression, which is simple, efficient, and widely used for healthcare-related binary classification.


---

📁 Dataset Used

The project uses the Cleveland Heart Disease Dataset, a well-known dataset for cardiovascular research.

Target Column:

HeartDisease →

1 = Disease Present

0 = No Disease




---

🔧 Technologies & Libraries

Python

NumPy

Pandas

Scikit-learn

Pickle (for saving the model)

StandardScaler (for feature scaling)



---

🧠 Model Workflow

1. Data loading and cleaning


2. Handling categorical features


3. One-Hot Encoding


4. Feature scaling using StandardScaler


5. Splitting dataset into train & test


6. Training Logistic Regression model


7. Saving trained model as best_model.pkl


8. User input-based prediction




---

🏥 User Prediction Flow

User provides medical details such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Resting ECG

Maximum Heart Rate

Exercise Angina

Oldpeak

ST Slope


The system: ✔ Converts inputs to model-ready format
✔ Scales the data
✔ Predicts Heart Disease: Yes/No
✔ Shows probability score


---

📊 Model Accuracy

Accuracy depends on train-test split & dataset quality.
(Logistic Regression generally performs between 75%–85% on this dataset.)


---

▶️ How to Run the Project

1. Clone the repository

git clone <repo-link>


2. Install requirements

pip install -r requirements.txt


3. Run the predictor

python predictor.py




---

📌 Project Structure

├── heart.csv
├── model_trainer.py
├── predictor.py
├── best_model.pkl
├── scaler.pkl
└── README.md


---

🧩 Future Improvements

Add a GUI using Tkinter or Streamlit

Deploy on web using Flask / FastAPI

Try advanced models like Random Forest / XGBoost

Add visual analytics



---

🧑‍🎓 Author

Gulam Mohiuddin Kadri
ID: 231003003039
