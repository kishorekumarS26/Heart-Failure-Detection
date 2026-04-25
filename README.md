                                                        Heart-Failure-Detection
Heart Failure Detection using Machine Learning. This project applies Random Forest and XGBoost models to predict heart disease from clinical data. Includes preprocessing, model evaluation, and visualizations like accuracy comparison, confusion matrix, and feature importance.

Introduction:

This project focuses on developing a machine learning model to predict the likelihood of heart failure based on clinical features. Heart failure is a critical medical condition that requires early detection for effective treatment. Accurate prediction models can assist healthcare professionals in timely diagnosis and decision-making.

In this project, we utilize a dataset containing patient health records such as age, sex, blood pressure, cholesterol levels, and other medical indicators. The implementation is carried out using Python with libraries like Pandas, NumPy, Matplotlib, and Scikit-learn.

Dataset:

The dataset used in this project is publicly available on Kaggle and consists of 918 instances with 12 features.

Features include:
Age: Age of the patient (years)
Sex: Gender (M: Male, F: Female)
ChestPainType: Type of chest pain (TA, ATA, NAP, ASY)
RestingBP: Resting blood pressure (mm Hg)
Cholesterol: Serum cholesterol (mm/dl)
FastingBS: Fasting blood sugar (1 if >120 mg/dl, else 0)
RestingECG: ECG results (Normal, ST, LVH)
MaxHR: Maximum heart rate achieved
ExerciseAngina: Exercise-induced angina (Y/N)
Oldpeak: ST depression value
ST_Slope: Slope of ST segment (Up, Flat, Down)
Target Variable:
HeartDisease:
1 → Heart disease present
0 → Normal

Methodology:

1. Exploratory Data Analysis (EDA)
Visualized feature distributions
Identified patterns and correlations
Used Matplotlib for plotting

3. Data Preprocessing
Handled categorical features using encoding
Prepared dataset for machine learning models

4. Data Splitting
Split dataset into training and testing sets using train_test_split

5. Model Training
The following models were used:
Random Forest Classifier
XGBoost Classifier

6. Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1 Score
Results

Both models performed well on the dataset.

Random Forest achieved strong baseline performance
XGBoost provided improved prediction accuracy and better generalization

The models were also evaluated using confusion matrices and feature importance plots to understand performance and key contributing features.

Conclusion:

This project successfully demonstrates the use of machine learning techniques to predict heart failure. The results indicate that ensemble models like Random Forest and XGBoost are effective in handling clinical datasets and can support early diagnosis in healthcare systems.

How to Use
Clone the repository

Install dependencies using:

pip install -r requirements.txt
Run the training script or Jupyter notebook
View model outputs and visualizations
Future Work
Hyperparameter tuning for improved accuracy
Deployment as a web application (Streamlit)
Integration with real-time healthcare or IoT systems
