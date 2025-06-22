# 🎓 Student Placement Prediction using AdaBoost

This project predicts whether a student is likely to get placed based on academic performance, certifications, and skill ratings using an AdaBoost classifier. A user-friendly web application is built with Streamlit, allowing real-time predictions and saving results to a MySQL database.

## 📌 Problem Statement

Predicting student placement outcomes can help institutions identify and guide students who may need additional training. This model provides an efficient and interactive way to assess placement likelihood based on multiple student parameters.

## 💻 Technologies Used

- **Python**
- **Streamlit** – Web app UI
- **AdaBoost Classifier (Scikit-learn)** – Prediction model
- **Joblib** – Model serialization
- **MySQL** – Backend data storage
- **NumPy** – Numerical operations

## 🧠 Model Details

- **Algorithm:** AdaBoostClassifier
- **Target:** `Placement Status` (1 = Placed, 0 = Not Placed)
- **Features:**
  - CGPA
  - Number of Internships
  - Projects Completed
  - Workshop/Certification Count
  - Aptitude Test Score
  - Soft Skills Rating
  - SSC & HSC Marks
  - Extracurricular Activities
  - Placement Training Attended

## 🚀 Web App Features

- Accepts input via sliders, text fields, and select boxes
- Predicts placement status in real time
- Displays results interactively using Streamlit
- Automatically saves predictions to MySQL database

## 📂 Folder Structure

-placement-prediction/
-│
-├── app.py # Streamlit application code
-├── Model_AdaBoost.pkl # Trained AdaBoost model
-├── requirements.txt # Python dependencies
-├── README.md # Project documentation

## 🗃️ Example Input & Output
- Input: CGPA = 8.1, Projects = 3, Internships = 1, Soft Skills = 7
- Output: ✅ Student is likely to be Placed

## 📌 Disclaimer
- This project is intended for educational use and should not be used as the sole basis for real-world decision-making in student career planning.
