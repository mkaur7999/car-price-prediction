# Car-Price-Prediction

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![Scikit-Learn](https://img.shields.io/badge/Library-ScikitLearn-orange.svg)

This repository consists of files required for end to end implementation and deployment of Machine Learning Car Price Prediction web application created with Flask and deployed on the Heroku platform.

## Table of Contents
  * [App Link](#app-link)
  * [About the App](#about-the-app)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)
  


## App Link
If you want to view the deployed model, click on the following link:<br />
[https://manpreet101803562-pricepredict.herokuapp.com/](https://manpreet101803562-pricepredict.herokuapp.com/)

## Objective
To develop a efficient and effective model which predicts the price of a used car according to user’s inputs.
To achieve good accuracy.
To develop a User Interface( UI ) which is user-friendly and takes input from the user and predicts the price.

## Overview about the App
The Car Price Prediction is a flask web application which predicts car prices based on given independent features like Car_Name,	Year,	Selling_Price,	Present_Price,	Kms_Driven,	Fuel_Type,	Seller_Type,	Transmission, and Owner. The dataset is available at Kaggle, and it's provided by cardekho.com. The app predicts the price of used Cars trained on the top of Random Forest Regressor model. The dataset contains information about used cars is taken from   Kaggle listed on www.cardekho.com. The trained model takes a data of used cars as a input and predict the Price of the Car as a output.

The code is written in Python 3.6.10. If you don't have Python installed, you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Flowchart of Methodology
![Flowchart of Methodology](https://github.com/mkaur7999/car-price-prediction/blob/main/templates/Flowchart%20of%20Methodology.png)

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually to deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

The next step would be to follow the instruction given in the [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Credits
* Dataset: The dataset contains information about used cars is taken from Kaggle listed on www.cardekho.com.
* Dataset Link: https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

