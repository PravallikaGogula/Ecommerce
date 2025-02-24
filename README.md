#Django E-commerce Application

A simple e-commerce web application built using Django. This project demonstrates fundamental Django concepts, including models, views, and template rendering, with SQLite as the database backend.

##Project Overview

This application includes two main models:

Product – Represents items in the e-commerce store, including name, price, stock, and image URL.

Offer – Represents discount offers that can be applied to products.

#Models

#Product Model:

name - The name of the product.

price - The price of the product.

stock - The number of available units.

img_url - URL to an image of the product.

#Offer Model:

code - A unique discount code.

description - A short description of the offer.

discount - The discount percentage applied by the offer.

Features

Basic CRUD (Create, Read, Update, Delete) functionality for managing products and offers.

Displaying products and their details on the website.

Applying discount codes for offers.

Technologies Used

Django - The web framework used to build the application.

SQLite - The database used for storing data.

HTML/CSS - For designing and rendering the web pages.

Installation

1. Clone the Repository

git clone https://github.com/rohitrathod2023/e-commerce-using-django.git

2. Navigate to the Project Directory

cd django-ecommerce

3. Install Required Dependencies

pip install -r requirements.txt

4. Run Migrations to Set Up the Database

python manage.py migrate

5. Start the Development Server

python manage.py runserver

6. Visit the Application in Your Browser

Open http://127.0.0.1:8000/products in your browser to view the application.
