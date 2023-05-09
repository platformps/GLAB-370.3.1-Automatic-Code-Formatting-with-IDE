# Exploring Flask: Building Dynamic Web Applications

## Description
In this lab, students will learn the fundamentals of building dynamic web applications with Flask, a popular web framework for Python. They will learn how to define routes, handle HTTP methods, use templates, and interact with databases using Flask's built-in support for SQL Alchemy.

## Instructions

- Begin by introducing Flask and its benefits for web development with Python.
- Explain how to install Flask using pip.
- Have the students create a basic Flask application with the following code:

```
from flask import Flask

app = Flask(name)

@app.route("/")
def home():
return "Hello, World!"

if name == "main":
app.run(debug=True)
```

- [ ] Explain how to define routes in Flask using the @app.route decorator.
- [ ] Have the students create a new route that takes a parameter and displays a personalized message based on the parameter.
- [ ] Explain how to use templates in Flask to create dynamic HTML pages.
- [ ] Have the students create a new template that uses variables to display dynamic content.
- [ ] Explain how to handle HTTP methods in Flask applications using the request.method attribute.
- [ ] Have the students create a new route that handles both GET and POST requests and processes form data.
- [ ] Explain how to use Flask's built-in support for SQL Alchemy to interact with databases.
- [ ] Have the students create a new model and database table using SQL Alchemy and display the table contents in a template.

