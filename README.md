🧠 AI Study Planner

Personalized End-Sem Study Hour Recommendation System

This project uses machine learning to recommend how many hours you should study for each subject — based on your mid-sem marks, urgency, days left, and current study habits.

📌 Features

Takes user inputs for:
Subject name
Current study hours
Mid-semester marks
Urgency level (1–10)
Days left before final exam
Automatically calculates recommended hours using:
Marks factor
Urgency factor
Time available factor
Trains a Linear Regression model to predict ideal study time

Shows:
Model performance (MSE, R² score)
Final study plan (table)
Generates a bar chart visualization of study hours

🛠️ Tech Stack

Python
Pandas – data manipulation
NumPy – numeric operations
Scikit-learn – ML model & evaluation
Matplotlib – graph visualization

📂 File Structure
ai_study_planner.py    → main project script
README.md              → project documentation

⚙️ How It Works

You enter number of subjects.
For each subject, you input:
Daily study hours
Mid-sem marks (out of 50)
Urgency (1–10)
Days left for exam
Model calculates "Recommended Hours" based on:
Lower marks = more hours
Fewer days left = more hours
Higher urgency = more hours
Linear Regression learns patterns
Final output shows:

Study hour recommendation per subject

A bar chart helps visualize priority subjects
