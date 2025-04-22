# 🎓 Student Performance Prediction System
## 🔎 Overview
In this end-to-end machine learning project, I developed a predictive model for student mathematics performance. After evaluating multiple regression algorithms, Linear Regression emerged as the optimal choice for this prediction task. The model achieved 📈good accuracy on the test dataset. The training data encompasses comprehensive student records including academic scores, demographic factors, and educational background metrics.

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


## 📂 Folder Structure
• 🖥️ UI: This contains UI website code

• 🔧 server: Contains the Python Flask server-related code

• 📊 model: Contains Python notebook for model building

## 📚 Required Libraries
`- pandas==2.0.31`
`- numpy==1.24.4`
`- seaborn==0.13.2`
`- matplotlib==3.7.5`
`- scikit-learn==1.3.2`
`- catboost==1.2.7`
`- xgboost==2.1.2`
`- dill==0.3.9`
`- Flask==3.0.3`

 **Deployment:** `AWS Elastic Beanstalk`


### 🚀 Installation & Setup
#### 1. Environment Setup
##### Create conda environment
`conda create -p venv python==3.8.0 -y`

##### ⚡ Activate environment
 `conda activate ./venv`

#### 2. Clone Repository:
`git clone https://github.com/Abdisamad001/mlproject.git`

#### 3. Install Dependencies
`pip install -r requirements.txt`

#### 4. Run Application
`python app.py`

🔄 Model Pipeline
Data Ingestion 📥
Load and split data into train and test sets

Data Transformation 🔄
Handle missing values
Feature scaling
Categorical encoding
Model Training 🎯
Multiple regression models evaluated
Hyperparameter tuning
Best model selection


#### 👨‍💻 Author
`Abdisamad Omar`

📧 Email: abdisamad.oma@gmail.com
🐱 GitHub: @Abdisamad001
#### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details
