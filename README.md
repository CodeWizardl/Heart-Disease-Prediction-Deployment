# Heart-Disease-Prediction 
A Flask web app to predict heart condition in a patient using KNN Machine Learning Model.

## Overview

A simple web application which uses Machine Learning algorithm to predict the heart condition of a person by providing some inputs about the person health like age, gender, blood pressure, cholesterol level etc built using `Flask`.

## Motivation

As being a Data and ML enthusiast I have tried many different projects related to the subject but what I have realised is that Deploying your machine learning model is a key aspect of every ML and Data science project. Everything thing I had studied or been taught so far in my Data science and ML journey had mostly focused on defining problem statement followed by Data collection and preparation, model building and evaluation process which is of course important for every ML/DS project but what if I want different people to interact with my models, how can I make my model available for end-users? I can't send them jupyter notebooks right!. That's why I wanted to try my hands on complete end-to-end machine learning project. 

- To get the Code for Exploratory data analysis/visualisations, different algorithms used and the model evaluation, click on the link mentioned below :
  **Link of jupyter notebook -** *[https://github.com/CodeWizardl/Heart-Disease-Prediction-Deployment-Master/blob/main/Heart%20Disease%20Prediction/heart_disease_prediction.ipynb](https://github.com/CodeWizardl/Heart-Disease-Prediction-Deployment-Master/blob/main/Heart%20Disease%20Prediction/heart_disease_prediction.ipynb)*

 ## Technical Aspect
 
 This Project is mainly divided into two parts:
 
 1. Exploring the dataset and traning the model using `Sklearn`.
 2. Building a web app using `flask`.

**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 

## Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```
pip install -r requirements.txt 
```

*To clone the repository*

```
git clone https://github.com/CodeWizardl/Heart-Disease-Prediction-Deployment-Master.git
```

*To Run the Application*

```
python app.py
```

## Future Work 

- **Improved Model Performance:** Investigate and implement strategies to enhance the model's predictive performance.

- **Enhanced User Interface Styling:** Add more appealing styling to the user interface for better user experience.

- **Deployment on Cloud Platforms:** Explore deployment options on cloud platforms such as Heroku, AWS, or others for wider accessibility.

- **Security Enhancements:** Implement additional security measures, such as input validation, to ensure the safety of user data.

## Screenshots
![Main](https://github.com/CodeWizardl/Heart-Disease-Prediction-Deployment-Master/assets/142290678/fcef351f-803d-4497-b7ad-29d50abe11d3)
![Result](https://github.com/CodeWizardl/Heart-Disease-Prediction-Deployment-Master/assets/142290678/9235e8d6-8fd6-458e-98af-afb52a84a0d0)
