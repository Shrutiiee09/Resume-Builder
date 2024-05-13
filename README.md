# Resume-Builder overview
Resume Builder Website

This is a web application built using Django framework for creating and managing resumes online. Users can sign up, create, edit, and download their resumes in various formats (e.g., PDF, Word). The website provides a user-friendly interface for building professional resumes effortlessly.

features

User authentication: Sign up, login, and logout functionalities.

Resume creation: Build resumes by filling out forms with personal, educational, and professional information.

Resume editing: Edit and update existing resumes.

Download resumes: Download resumes in different formats (e.g., PDF, Word).

Responsive design: Compatible with various devices and screen sizes.


Requirements

Python 3.x

Django 3.x

wkhtmltopdf (for generating PDF resumes)


Installation

Clone the repository to your local machine:

git clone https://github.com/yourusername/resume-builder.git

Navigate to the project directory:

cd resume-builder

Create a virtual environment:

python -m venv env

Activate the virtual environment:

On Windows:

env\Scripts\activate

On macOS and Linux:

source env/bin/activate

Install the required packages:

pip install -r requirements.txt

Install wkhtmltopdf for generating PDF resumes. You can download it from here and follow the installation instructions for your operating system.

Usage

Run database migrations:

python manage.py migrate

Create a superuser to access the Django admin panel:

python manage.py createsuperuser

Start the development server:

python manage.py runserver

Open a web browser and go to http://localhost:8000 to access the website.

Contributing

Contributions are welcome. Feel free to submit pull requests or open issues for any improvements or suggestions.

License
This project is licensed under the MIT License - see the LICENSE file for details.
