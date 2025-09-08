## AI-Based Solution for Proactive School Dropout Risk Prediction
This project leverages Artificial Intelligence to identify at-risk students and prevent school dropout through proactive intervention strategies. By analyzing multidimensional data including academic performance, behavior patterns, attendance, and socio-familial context, our solution helps educational institutions implement data-driven prevention measures.
### 🎯 Objectives
- Identify at-risk students using multidimensional data analysis (academic performance, behavior, attendance, socio-familial context)
- Understand underlying dropout mechanisms by exploring complex interactions between academic, psychological, economic, and environmental variables
- Support educational decision-making through proactive, data-driven prevention strategies replacing reactive approaches
### 📁 Dataset
The dataset used in this project was generated with the help of artificial intelligence to simulate data related to school dropout. This approach was necessary because real student data is usually confidential and protected by strict regulations, making it inaccessible for research purposes.

### 🧠 Project Workflow
#### Exploratory Data Analysis (EDA)
- Statistical analysis of student demographics and performance patterns
- Visualization of risk factors distribution and correlations
- Identification of key dropout indicators
#### Data Preprocessing & Feature Engineering
- Cleaning and standardizing student data
- Encoding categorical variables (participation levels, transport accessibility, behavior patterns)
- Creating multidimensional risk indicators:
        
        - Academic Difficulty Index
        - Student Motivation Score
        - Absenteeism Index
        - Transport Accessibility Score
        - Economic/Family Stability Indicators
### Risk Assessment Modeling
#### Problem Type: 
Binary Classification (Dropout Risk: 1 = at-risk, 0 = stable)
#### Class Imbalance Handling: 
SMOTE (Synthetic Minority Oversampling Technique)
#### Model Selection:
Ensemble approach with voting classifier
#### Model Selection Process
Because this was a binary classification task (dropout vs. no dropout), we experimented with a wide range of models to identify the most reliable one including XGBoost, Gradient Boosting, SVM, AdaBoost, Decision Tree, K-NN, and Logistic Regression , the top three models consistently delivered the highest performance :
<img width="781" height="132" alt="image" src="https://github.com/user-attachments/assets/d0218ea8-da24-45e7-a63f-d6a9f247e6bf" />
To maximize prediction accuracy, we combined the three best-performing models (MLP, LightGBM, Random Forest) into a Voting Classifier. This ensemble approach makes the final decision based on majority voting among the models, leading to more stable and robust predictions.

#### Model Interpretability
We used SHAP for local and global prediction explanations to identify features and support the educational team .
### Personalized Intervention Recommendations
- Academic support strategies (tutoring, course reorientation)
- Transport solutions (school bus organization, mobility scholarships)
- Psychological support for family instability
- Economic assistance (study grants, free meals, school supplies)
### 📈 Results
Best Model Performance (Voting Classifier):
- Accuracy: 98.68%
- Precision: 98.43%
- Recall: 98.95%
- F1-Score: 98.70%
### 🌐 Web Platform Features
Our solution includes a comprehensive web platform for educational teams:
-Student Risk Dashboard - Real-time dropout risk assessment
- Predictive Analytics - AI-powered early warning system
- Intervention Tracking - Monitor implemented prevention strategies
- User Management - Role-based access for teachers, counselors, administrators
- Data Visualization - Interactive charts and risk factor analysis

<img width="2590" height="1485" alt="image" src="https://github.com/user-attachments/assets/1e0f3e25-56a3-4a59-9d9b-b6050bfc573a" />
<img width="2570" height="1474" alt="image" src="https://github.com/user-attachments/assets/e4d0296a-351b-4141-a228-c4ec584bcc6f" />
<img width="2511" height="1440" alt="image" src="https://github.com/user-attachments/assets/590504da-bb6e-4a82-8488-2bd89bbdcc02" />
<img width="2589" height="1485" alt="image" src="https://github.com/user-attachments/assets/9ff1d575-6f23-4c72-a032-67396e86a6fa" />




### 👥 Team & Competition
This project was developed in collaboration with Louiza Dahmani and Nour Amani Saal as part of our participation in the National Olympiad in Programming & AI.


## This project aims to support educational institutions in Algeria and beyond in their mission to ensure every student has the opportunity to complete their education successfully.

