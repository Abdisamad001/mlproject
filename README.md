# 🎓 Student Performance Prediction System

## 🔎 Overview
In this end-to-end machine learning project, I developed a predictive model for student mathematics performance. After evaluating multiple regression algorithms, Linear Regression emerged as the optimal choice for this prediction task. The model achieved 📈 87.97% accuracy on the test dataset. The training data encompasses comprehensive student records including academic scores, demographic factors, and educational background metrics.

The project utilized:
- 📊 1000 student records for training and testing 
- 🔍 Feature engineering for both categorical and numerical variables
- 🛠️ Standardization and one-hot encoding preprocessing
- 📋 80-20 train-test split for model validation

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/python-3.8.0-blue)
![Flask](https://img.shields.io/badge/Flask-3.0.3-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.2-orange)
![Pandas](https://img.shields.io/badge/pandas-2.0.3-yellow)
![NumPy](https://img.shields.io/badge/numpy-1.24.4-blue)
![CatBoost](https://img.shields.io/badge/catboost-1.2.7-red)
![XGBoost](https://img.shields.io/badge/xgboost-2.1.2-purple)
![AWS](https://img.shields.io/badge/AWS-ElasticBeanstalk-orange)

## 🌐 Live Demo
The application is deployed and accessible at:
[Student Performance Predictor](http://studentmathgrade-env-1.eba-qhcwims9.eu-central-1.elasticbeanstalk.com/)

## ⭐ Features
- 📊 Predicts mathematics scores based on:
  - Gender
  - Race/Ethnicity
  - Parental Level of Education
  - Lunch Type
  - Test Preparation Course
  - Reading Scores
  - Writing Scores
- 💻 User-friendly web interface
- 🔄 Advanced ML pipeline with multiple models
- 🤖 Automated data preprocessing

## 📚 Required Libraries
- pandas 2.0.3
- numpy 1.24.4
- seaborn 0.13.2
- matplotlib 3.7.5
- scikit-learn 1.3.2
- catboost 1.2.7
- xgboost 2.1.2
- dill 0.3.9
- Flask 3.0.3
    
**Deployment:** AWS Elastic Beanstalk

## 📂 Project Structure
```python
MLPROJECT/
├── .ebextensions/         
│   └── python.config
├── .vscode/              
├── artifacts/            
├── catboost_info/        
├── logs/                
├── mlproject.egg-info/  
├── notebook/             
├── src/                 
│   ├── components/      
│   │   ├── __init__.py
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   ├── pipelines/      
│   │   ├── __init__.py
│   │   ├── predict_pipeline.py
│   │   └── training_pipeline.py
│   ├── __init__.py
│   ├── exception.py    
│   ├── logger.py     
│   └── utils.py      
├── templates/         
│   ├── index.html   
│   └── home.html    
├── static/            
│   └── images/      
├── venv/             
├── .gitignore      
├── app.py           
├── application.py 
├── README.md       
├── requirements.txt
└── setup.py

🚀 Installation & Setup
1. Environment Setup
# Create conda environment
conda create -p venv python==3.8.0 -y

# Activate environment
conda activate ./venv

2. Clone Repository
git clone https://github.com/Abdisamad001/mlproject.git

3. Install Dependencies
pip install -r requirements.txt

4. Run Application
python app.py

🔄 Model Pipeline
Data Ingestion 📥 - Load and split data into train and test sets
Data Transformation 🔄
Handle missing values
Feature scaling
Categorical encoding
Model Training 🎯
Multiple regression models evaluated
Hyperparameter tuning
Best model selection
☁️ Deployment
The application is deployed on AWS Elastic Beanstalk:

Region: EU Central 1
Python Environment: 3.8.0
Elastic Beanstalk Configuration in .ebextensions
👨‍💻 Author
Abdisamad Omar

📧 Email: abdisamad.oma@gmail.com
🐱 GitHub: @Abdisamad001
📄 License
This project is licensed under the MIT License - see the LICENSE file for details
