# Assignment 8: Develop a Simple Web Application Using Flask

## Objective

To create a simple web application using the Flask framework to understand the key concepts of web application development in Python.

## Expected Capabilities

- Setup a Flask project
- Develop a simple web application with defined routes

## Instructions

### Part 1

**Setup Flask Environment**

Install Flask and setup a basic project directory.

```
pip install Flask
```

**Create a Simple Web App**

Create a simple Flask web application that displays a welcome message.

```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
 return 'Welcome to my web app!'

if __name__ == '__main__':
 app.run(debug=True)
```

## Tasks

### Task 1: Develop a Simple Flask Application

Follow the instructions to setup and run a basic Flask application.

```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
 return 'Welcome to my web app!'

if __name__ == '__main__':
 app.run(debug=True)
```

## Submission Instructions

Submit the screenshot of your web application running in a browser.

## Checklist

- [ ] Flask Installed
- [ ] Basic App Created
- [ ] App Running in Browser

## Check for Understanding

**What is Flask mainly used for?**

- Data Analysis
- Web Development
- Image Processing

**Answer:** [Your answer here]

**In Flask, which method defines a route?**

- @route
- @app.route
- @flask.route

**Answer:** [Your answer here]