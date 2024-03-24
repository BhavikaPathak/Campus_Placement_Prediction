# Campus Placement Prediction End to End Deployment

Project aims to predict campus placement outcomes for students using machine learning techniques. The predictive model is designed to assist educational institutions and recruiters in making informed decisions during the placement process.

## Website Link (Credit Card Default Prediction)

https://campus-placements.herokuapp.com

## Technical aspect
Python 3.7
Front-end: HTML, CSS, Bootstrap
Back-end: Flask framework
IDE: Jupyter Notebook, PyCharm
Deployment: Horeku

# How to run this app?

Code is written in Python 3.7. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.

- Create virtual environment: conda create -n myenv python=3.7
- Activate the environment: conda activate myenv
- Install the packages: pip install -r requirements.txt
- Run the app: python app.py

# Data Collection

The dataset is collected from Kaggle.

# Model Creation and Evaluation

- Various classification algorithms like Logistic Regression, Random Forest, Decision Tree, Naïve Bayes, Support Vector Machine tested.
- Random Forest , SVM , Decision Tree and Logistic regression were given better results.SVM was chosen for the final model training and testing.
- Model performance evaluated based on accuracy, confusion matrix, classification report.


# Model Deployment

The final model is deployed on Horeku using Flask framework .
