# Suicide Thought Detection with Django and MySQL
This is a machine learning based web application that detects suicide thoughts in people. 
It uses Django as the web framework and MySQL as the database management system. 
The application is designed to help people who may be struggling with suicidal thoughts and 
provide them with resources and support to help them.


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for 
development and testing purposes.


### Prerequisites
* Python 3.x
* Django
* MySQL
* scikit-learn
* Tensorflow/Keras


### Installing
#### 1- Clone the repository to your local machine.
    * git clone https://github.com/[username]/suicide-thought-detection.git
#### 2- Navigate to the project directory and create a virtual environment.
    * cd suicide-thought-detection
    * python3 -m venv env
#### 3- Activate the virtual environment.
    * source env/bin/activate
#### 4- Install the required packages.
    * pip install -r requirements.txt
#### 5- download models
    steps:
        1- download models
        2- place it in this format *fyp_project/models*
#### 6- download and install mysql-workbench
#### 7- create mysql-connection into workbench
#### 8- create schema with the name of *reg_user*
#### 9- create table and add 2 fields with *email* and *password*
#### 10- run the commands
    steps:
        1- python/python3 manage.py collectstatic
        2- python/python3 manage.py makemigrations
        3- python/python3 manage.py migrate
#### 11- run the app
    $  python/python3 manage.py runserver


## Deployment
The application can be deployed on a web server for production use. It is recommended to 
use a production-ready web server such as Apache or Nginx for better performance and security.


## Built With
    Django - The web framework used
    MySQL - Database management system
    scikit-learn - Machine learning library for Python
    Tensorflow/Keras - Deep learning framework


## Author
[Ahmad Mujtaba](http://www.ahmad-mujtaba.com/)
