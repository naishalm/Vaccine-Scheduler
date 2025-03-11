# Vaccination

The Vaccination project is a web-based application designed to educate parents on how to keep track of their child's immunizations given, due, and updated. The main goal of the project is to provide an easy-to-use platform for parents to manage their child's vaccination schedule and to help reduce the risk of preventable diseases.


## Functionality Features

The Vaccination project includes the following features:
  * Vaccine reminder: This feature allows parents to receive reminders about when their child's vaccines are due. They can choose to receive reminders via email, SMS, or push notifications.
  * Immunization schedule: The Vaccination project provides an appropriate immunization schedule for children based on their age and medical history. This ensures that children receive the correct vaccinations at the right time.
  * Information about vaccines: The project provides detailed information about each vaccine, including the diseases it protects against, possible side effects, and recommended age for administration.
  * Ask doctor facilities: Parents can ask any questions they have about vaccines and immunization by sending a message to a healthcare professional. They can also request an appointment with a doctor or immunization clinic.


## Installation

To run this application, you will need to have Python and Flask installed on your system. You can install Flask using pip: `pip install Flask`

### You will also need to install the following libraries:
  * passlib
  * Flask-Mail
  * datetime

### You can install these libraries using pip:
  `pip install passlib Flask-Mail datetime`


## Usage:

To start the application, run the following command in your terminal:
$ python run.py

This will start the Flask development server and you should be able to access the web site by navigating to http://localhost:8082/ in your web browser.

## File Structure

The file structure for this web site is as follows:
    • run.py: This is the main Flask application file.
    • templates/: This directory contains the HTML templates used to render the web pages.
    • static/: This directory contains static assets such as CSS and JavaScript files.
    • db.py: This file handles all the database operations

## Features

This web site includes the following features:
    • User authentication using passlib
    • Email notifications using Flask-Mail
    • Session management using Flask's session object
    • Password reset functionality
    • Date and time manipulation using datetime module
