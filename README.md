# Customer-Churn-Prediction-Using-Artificial-Neural-Network

<p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/110115053-f7428980-7dce-11eb-8056-92ce38eb1c22.png"></p>

## Overview

Customer churn prediction is to measure why customers are leaving a business. I am using here Telco Customer Data from Kaggle. Will build a deep learning model to predict the churn and use precision, recall, f1-score to measure performance of the model.



## Technical Aspect
This project is divided into two part:
1. Creating the front end using [HTML](https://github.com/mpfouziya/Customer-Feedabck-Web-Application-Using-Python-PostgreSQL-Flask-and-Heroku/tree/main/CustomerFeedbackApp/template) and [CSS](https://github.com/mpfouziya/Customer-Feedabck-Web-Application-Using-Python-PostgreSQL-Flask-and-Heroku/tree/main/CustomerFeedbackApp/static). Use SQLAlchemy as a layer of abstraction to PostgreSQL from Python.
2. Sending the input data to a designated mail address. Code : [send_mail.py](https://github.com/mpfouziya/Customer-Feedabck-Web-Application-Using-Python-PostgreSQL-Flask-and-Heroku/blob/main/CustomerFeedbackApp/send_mail.py) 
3. Building and hosting the Flask web app on Heroku.
    

## Installation
The Code is written in Python 3.9.1 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img width="159" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/108682128-5f5cba00-7509-11eb-9ab4-2cc02f7971c0.png">](https://www.postgresql.org/) [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) <img width="80" alt="html" src="https://user-images.githubusercontent.com/37532698/108952721-77584900-7683-11eb-8dec-5376533d43cf.png"> <img width="64" alt="css" src="https://user-images.githubusercontent.com/37532698/108952837-a4a4f700-7683-11eb-8740-e044f1e34651.png"> 



