# Project-4
## Alzheimer's Disease Progression Prediction

### Overview
#### This project leverages machine learning to predict the progression of Alzheimer's disease based on patient demographics, cognitive scores, and risk factors. The goal is to identify early indicators of disease progression and assist in personalized treatment planning. 

### Dataset
#### The dataset includes various features relevant to Alzheimer's prediction:
- Cognitive Assessment: MMSE (Mini-Mental State Exam), Functional Assessment
- Behavioral and Memory Symptoms: Memory Complaints, Confusion, Disorientation, Personality Changes, Forgetfulness
- Risk Factors: Cardiovascular Disease, Diabetes, Depression, Hypertension
- Lifestyle Factors: Smoking, Alcohol Consumption, Physical Activity, Diet Quality, Sleep Quality
- Blood Pressure & Cholesterol: Systolic BP, Diastolic BP, Total Cholesterol, LDL, HDL, Triglycerides

### Model Implementation
#### The model is built using: 
- Random Forest Classifier for prediction
- GridSearchCV for hyperparameter tuning
- Feature importance analysis to identify key predictors
- SQLite database integration for scalable data storage

### Performance
- Achieved 79% accuracy on test data
- Identified key risk factors contributing to Alzheimer's progression
- Precision and recall metrics indicate strong predictive capability:
    - Class 0 (Non-Alzheimer’s): 82% Precision, 86% Recall
    - Class 1 (Alzheimer’s): 72% Precision, 66% Recall
- Optimized using hyperparameter tuning

### Installation and Setup
1. Clone the Repository
2. Install Dependencies
3. Setup the database

### How to Run the Model
1. Train the Model
    - Run the training script
    - This will: 
        - Load and clean the dataset
        - Train the Random Forest Classifier
        - Optimize the model
        - Save the trained model 
2. Evaluate Model Performance
    - This will: 
        - Load the trained model
        - Figure accuracy and classification metrics
        - Generate a confusion matrix
3. Export Data for Tableau
    - To generate CSV files for visualization
        - This will create:
            - alzheimers_predictions.csv - Model predictions vs actual values
            - alzheimers_feature_importance.csv - Top contributing features
            - alzheimers_patient_data.csv - Demographics and cognitive scores

### Tableau Dashboard
#### 

### Future Improvements
- Integrate Deep Learning (LSTM, CNNs) for enahnce prediction
- Expand dataset with MRI and PET scan data
- Deploy as a web application

### Resources
- Kaggle - Alzheimer's research community provided dataset
- Class instruction/rewatch recordings
- Group work
- Tutoring sessions
- Chatgpt
