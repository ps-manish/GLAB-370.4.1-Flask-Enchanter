# GLAB-370.4.1-Flask-Enchanter

## Welcome to the "Flask Enchanter: Setting Up Flask and Virtual Environment" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on an exciting journey to set up the **Flask framework** and a **virtual environment** for your Python projects. Get ready to dive into the world of web development with Flask and ensure a clean and isolated development environment!

### Prerequisites

Before we begin, make sure you have the following:

- Basic knowledge of Python syntax.
- Python and pip installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: Installing Flask](#step-2-installing-flask)
- [Step 3: Setting Up a Virtual Environment](#step-3-setting-up-a-virtual-environment)
- [Step 4: Creating a Flask Project](#step-4-creating-a-flask-project)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's begin our adventure into the world of **Flask** and **virtual environments**. Flask is a popular and lightweight web framework for Python, and a virtual environment ensures a clean and isolated development environment for your projects. In this lab, we'll explore how to install Flask and set up a virtual environment.

### Step 2: Installing Flask

To start our journey with Flask, we need to install it using the `pip` package manager. Open a command-line interface and execute the following command:

```
pip install flask
```

This command will download and install the Flask package, enabling us to use the framework in our projects.

### Step 3: Setting Up a Virtual Environment

Next, let's set up a **virtual environment** to ensure a clean and isolated development environment for our Flask projects. A virtual environment allows us to install packages specific to a project without interfering with other Python installations.

1. Open a command-line interface.
2. Navigate to the desired directory for your Flask project.
3. Execute the following command to create a virtual environment:

   ```
   python -m venv myenv
   ```

   This command will create a new directory called `myenv` that contains the virtual environment.

4. Activate the virtual environment based on your operating system:

   - **Windows**:

     ```
     myenv\Scripts\activate
     ```

   - **macOS/Linux**:

     ```
     source myenv/bin/activate
     ```

   After executing the command, you'll notice the command prompt changes to indicate that you're now working within the virtual environment.

### Step 4: Creating a Flask Project

Now that Flask is installed and the virtual environment is set up, we can create a Flask project.

1. Within your activated virtual environment, create a new directory for your Flask project.
2. Navigate into the project directory and create a new Python file, e.g., `app.py`.
3. Open the Python file in your preferred code editor.
4. Import Flask and define a basic Flask application:

   ```python
   from flask import Flask

   app = Flask(__name__)

   @app.route("/")
   def hello():
       return "Hello, Flask!"

   if __name__ == "__main__":
       app.run()
   ```

   This code sets up a simple Flask application with a single route that returns "Hello, Flask!" when you access the root URL.

5. Save the file.

### Step 5: Challenge

Now it's time for an exciting challenge! Customize the Flask application you created. Add new routes, render HTML templates, or retrieve data

 from a database. Experiment with different Flask features to build a small web application.

### Step 6: Conclusion

Congratulations on completing the "Flask Enchanter: Setting Up Flask and Virtual Environment" Guided Lab! You've learned how to install Flask and set up a virtual environment, setting the foundation for building powerful web applications.

Remember to explore Flask's extensive documentation to discover the full potential of the framework. Flask offers numerous features and extensions that empower you to create dynamic and engaging web applications.

Feel free to reach out if you have any questions. Happy coding, and may your Flask-powered web applications thrive! 🎉
