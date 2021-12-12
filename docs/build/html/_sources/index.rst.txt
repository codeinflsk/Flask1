.. Flask1 documentation master file, created by
   sphinx-quickstart on Sun Nov 28 22:59:06 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Flask1's documentation!
==================================

Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapperaround Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

Flask offers suggestions, but doesn't enforce any dependencies or project layout. It is up to the developer to choose the tools and libraries they want to use. There are many extensions provided by the community that make adding new functionality easy.

Installing

Install and update using pip:

$ pip install -U Flask
A Simple Example
# save this as app.py
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello, World!"


$ flask run
  * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)





















.. toctree::
   :maxdepth: 2
   :caption: Contents:

