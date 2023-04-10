# Server Monitoring Tool Backend
This repository contains the backend code for the Server Monitoring Tool. The backend is built using Django, a Python web framework, and provides RESTful API endpoints for the frontend app to communicate with.

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/Ikshan-Tango/hacklipse-backend.git
$ cd sample-django-app
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd project
(env)$ python manage.py runserver

## Requirements
1. Python 3.x
2. Django 3.x
3. Django REST framework

## Documentation of the project
Refer to the following docs to take a deep dive into the project!
```sh
[docs](https://docs.google.com/document/d/1XG_Wq7_T-m-j6jDAyQi5NdJNsQeT9LohQUMtA1qT3E4/edit?usp=sharing).
```
