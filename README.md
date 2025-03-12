# HeartDisease_Detection
This project predicts the possibility of heart disease using Logistic Regression in Machine Learning. It includes data preprocessing, model training, evaluation, and hyperparameter tuning.
<br>
<p>

 # 📌 Objective
The main goal of this project is to build a predictive model that can determine whether a patient is at risk of heart disease based on various medical attributes such as age, blood pressure, cholesterol levels, and other clinical parameters.
<br>
By leveraging Machine Learning, this model can assist healthcare professionals in early diagnosis, thus improving treatment outcomes and reducing risks.

# 📌 About the Dataset
The dataset is sourced from **UCI Heart Disease Dataset**, and the model has been built following standard Machine Learning practices.<br>
The dataset consists of 13 input features and 1 target variable (Heart Disease presence: 0 = No, 1 = Yes):<br>
Feature -->	Description <br>
age	-->Age of the patient <br>
sex	-->Gender (1 = Male, 0 = Female) <br>
cp -->	Chest pain type (4 categories: 0-3) <br>
trestbps	-->Resting blood pressure (mm Hg) <br>
chol	-->Serum cholesterol (mg/dL) <br>
fbs-->	Fasting blood sugar > 120 mg/dL (1 = True, 0 = False) <br>
restecg	--> Resting ECG results (0-2) <br>
thalach	--> Maximum heart rate achieved <br>
exang	--> Exercise-induced angina (1 = Yes, 0 = No) <br>
oldpeak-->	ST depression induced by exercise relative to rest <br>
slope	--> Slope of the peak exercise ST segment <br>
ca	--> Number of major vessels colored by fluoroscopy (0-4) <br>
thal	--> Type of thalassemia defect (0-3) <br>
target -->	Presence of heart disease (1 = Disease, 0 = No Disease)<br>

##  Project Overview
 **Data Preprocessing**: Handling missing values, encoding categorical data, and scaling features  
 **Exploratory Data Analysis (EDA)**: Understanding feature distributions and correlations  
 **Machine Learning Model**: Implemented **Logistic Regression** for classification  
 **Model Evaluation**: Accuracy, precision, recall, F1-score, ROC-AUC score  
 **Hyperparameter Tuning**: Improved model performance with optimized parameters  

This project helped me understand the **practical application of AI & ML in healthcare analytics** while refining my skills in **Python, data analysis, and model optimization**. 

# 📌 Results & Conclusion
The Logistic Regression model performed well with an accuracy of 85-90% (varies based on data split).
The ROC-AUC score was high, indicating a good ability to distinguish between heart disease and non-heart disease cases.
Key risk factors identified included age, cholesterol levels, chest pain type, and exercise-induced angina. <br>
🔹 Final Thoughts <br>
Machine Learning models can be valuable tools in healthcare for early heart disease prediction.
The model can be improved further by using advanced techniques like Decision Trees, Random Forest, or Deep Learning.
The project demonstrates how data analytics and AI can be used to solve real-world health problems. 🚀


## 📌 **How to Run This Project**
### ** Method 1: Open in Google Colab (Recommended)**
Click below to run the project online **without any setup**:  
 [Open in Colab]

### ** Method 2: Run Locally**
1. **Clone this repository**:
   ```sh
   git clone https://github.com/OfficiallyNikita/HeartDisease_Detection.git
   cd HeartDisease_Detection
  

