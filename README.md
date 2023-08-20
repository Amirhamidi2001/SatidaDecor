# SatidaDecor
SatidaDecor

SatidaDecor is an website and blog developed with Django.

The SatidaDecor website showcases the Posts and services offered by SatidaDecor, a company that specializes in interior design and decoration. The website features a gallery of projects, a list of services, a contact form, and information about the company.

The SatidaDecor blog is a platform for the company to share their expertise in interior design and decoration. The blog features articles on various topics related to interior design, such as color schemes, furniture placement, and lighting. The blog also includes case studies of projects completed by SatidaDecor.

Features

    Post browsing and search
    Post categorization
    Order tracking
    Admin panel for managing Posts, categories, and orders

Requirements

    Python 3.10
    Django 4.2
    Additional dependencies can be found in the requirements.txt file.

Installation

Clone the repository:

bash

    git clone https://github.com/Amirhamidi2001/SatidaDecor.git

Change into the project directory:

bash

    cd SatidaDecor

Create a virtual environment:

bash

    python3 -m venv venv

Activate the virtual environment:

bash

    source venv/bin/activate

Install the dependencies:

bash

    pip install -r requirements.txt

Set up the database:

bash

    cd core
    python manage.py makemigrations
    python manage.py migrate

Create a superuser for the admin panel:

bash

    python manage.py createsuperuser

Start the development server:

bash

    python manage.py runserver

Open your web browser and visit http://localhost:8000 to access the SatidaDecor website.

Configuration

    The main configuration file for the project is settings.py, located in the core directory.
    Database settings can be adjusted in the DATABASES section of settings.py.
    Static files and media files are stored in the static and media directories, respectively.
    Email settings can be configured in the EMAIL_BACKEND and related settings in settings.py.

Contributing

Contributions to SatidaDecor are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the existing code style and include appropriate tests for your changes.
License

This project is licensed under the MIT License.
Acknowledgements

    The SatidaDecor website was developed as part of a Django web development tutorial.
    The template used for the front-end design is from Bootstrap.
    Images used in the website are for demonstration purposes only and are sourced from Unsplash.

You can see the website in this URL:

    https://satidadecor.pythonanywhere.com/
