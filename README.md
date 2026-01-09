#Autism Prediction System using Machine Learning
📌 Project Overview
The Autism Prediction System is a Machine Learning–based project developed to predict Autism Spectrum Disorder (ASD) using behavioral and screening questionnaire data.
This system helps in early detection support by analyzing patterns in user responses through classification algorithms.

🎯 Objectives
To analyze autism screening data
To preprocess and clean the dataset
To build a machine learning classification model
To predict whether autism traits are detected or not

🛠️ Technologies Used
Python
Jupyter Notebook
Pandas & NumPy – Data handling
Scikit-learn – Machine Learning
Random Forest Classifier

📂 Dataset
Source: Kaggle (Autism Screening Dataset)
Type: CSV file
Features:
Behavioral scores (A1–A10)
Age
Gender
Ethnicity
Relation
Country of residence
Target Variable:
Class/ASD (Autism Detected / Not Detected)

🔄 Workflow Diagram
Dataset Collection
        ↓
Data Preprocessing
        ↓
Feature Encoding
        ↓
Train–Test Split
        ↓
Model Training
(Random Forest)
        ↓
Model Evaluation
        ↓
Prediction Output

⚙️ Methodology
Loaded autism screening dataset
Handled missing values and removed unnecessary columns
Encoded categorical features into numerical values
Split data into training and testing sets (80/20)
Trained a Random Forest Classifier
Evaluated the model using accuracy, confusion matrix, and classification report
Tested the model with new sample input

📈 Model Evaluation
Accuracy: High accuracy achieved on test data
Metrics Used:
Accuracy Score
Confusion Matrix
Precision, Recall, F1-score

🧪 Sample Prediction
The system can take new user input data and predict:
Autism Detected
No Autism Detected
⚠️ This system is for educational and screening purposes only and is not a medical diagnosis tool.

✅ Project Status
✔ Completed
✔ Tested
✔ Interview & CV Ready

📌 Future Enhancements
Add a web interface using Flask
Improve model generalization
Deploy the model online
Add data visualization

👩‍💻 Author
Dhruvi Prajapati
Bachelor of Engineering – Information Technology
Machine Learning & Data Analytics Enthusiast

⭐ Acknowledgement
Kaggle for providing the dataset
Scikit-learn documentation
Jupyter Notebook environment
