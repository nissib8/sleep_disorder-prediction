💤 Sleep Disorder Prediction System

A machine learning–based web application that predicts sleep disorders such as Insomnia and Sleep Apnea based on lifestyle and health-related factors. The project aims to assist in early awareness and encourage timely medical consultation.

📌 Problem Statement

Sleep disorders significantly affect physical health, mental well-being, and productivity. Many people remain undiagnosed due to lack of awareness. This project uses machine learning to analyze user data and predict the likelihood of a sleep disorder.

🎯 Objectives

Predict whether a person has:

No Sleep Disorder

Insomnia

Sleep Apnea

Provide a simple, interactive interface for users

Demonstrate the application of ML in healthcare analytics

🧠 Machine Learning Approach

Type: Supervised Classification

Model Used: Random Forest Classifier (can be changed)

Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

📊 Features Used

Age

Gender

Occupation

Sleep Duration

Quality of Sleep

Physical Activity Level

Stress Level

BMI Category

Blood Pressure

Heart Rate

Daily Steps

🛠️ Tech Stack

Programming Language: Python

Libraries:

pandas

numpy

scikit-learn

matplotlib / seaborn

Web Framework: Streamlit

IDE: VS Code / Jupyter Notebook


🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/sleep-disorder-prediction.git
cd sleep-disorder-prediction

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Train the Model (Optional)
python train_model.py

4️⃣ Run the Web App
streamlit run app.py

🖥️ Output

User inputs health and lifestyle data

The system predicts the sleep disorder category

Result is displayed instantly on the web interface

📈 Future Enhancements

Add more advanced models (XGBoost, Neural Networks)

Integrate real-time wearable data

Provide personalized sleep improvement suggestions

Deploy the app online (Streamlit Cloud / Render)

⚠️ Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical diagnosis.
