Student Management System
=========================

This is a Student Management System built using Django 5, HTML5, CSS3, and Bootstrap 5 with a Bootswatch theme for enhanced styling.

Features
--------

* Manage students effectively.
* Built with Django's powerful framework.
* Styled using modern web technologies (Bootstrap 5, Bootswatch).
* Easy-to-use interface.

Installation
------------

Follow the steps below to set up the project on your local machine:

### 1. Clone the Repository

Clone this repository to your local machine:

    git clone <repository-url>
    cd Student-Management-System

2. Create a Virtual Environment

Create a virtual environment to manage dependencies:

    python -m venv venv

3. Activate the Virtual Environment

Activate the virtual environment:

On macOS/Linux:
    
    source venv/bin/activate

On Windows:
    
    venv\Scripts\activate

4. Install Dependencies

Install the required dependencies using:

    pip install -r requirements.txt

5. Run Migrations

Set up the database by running the migrations:

    py manage.py makemigrations
    py manage.py migrate

6. Create a Superuser

Create an admin user to access the Django Admin interface:

    py manage.py createsuperuser

Follow the prompts to enter a username, email, and password.

7. Run the Application

Start the development server:

    py manage.py runserver

Usage

Open your browser and go to http://127.0.0.1:8000/ to access the application.

Log in to the admin panel at http://127.0.0.1:8000/admin/ with the superuser credentials.

Screenshots:
![alt text](https://raw.githubusercontent.com/BobsProgrammingAcademy/Student-Management-System/refs/heads/master/students/static/images/homepage.png)