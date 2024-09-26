# Ousa Car Rental System
Ousa Car Rental System is a web-based platform built using the Django framework that facilitates the rental of cars in Kenya.<br /> <br />
The system is designed to make the process of renting vehicles more accessible and efficient for both car rental companies and customers. <br /> <br />
User can login then rent a car<br /> <br /> 
User can also download the bill generated.

# Key Features
User Authentication: Users can create accounts, log in, and manage their profiles.
Car Listings: A comprehensive list of available cars for rent is provided, complete with details such as model, rental price, and availability.
Car Rental: Users can select and rent cars with a few simple clicks.
Billing and Invoice Generation: After a successful rental, users can download an automatically generated invoice for their transaction.
Admin Panel: Rental companies or system administrators can manage cars, users, and rentals through Django’s built-in admin interface.
Responsive Design: The platform is designed to work on both desktop and mobile devices, ensuring accessibility on the go.
Secure Data Handling: Passwords are hashed and data is managed securely using Django's robust security features.

## About Django : <br /> <br />
Django is an MVT web framework that is used to build web applications.Django has an in-built administration interface which lets you handle your models, user/ group permissions and to manage users. With model interface in place, there is no need for a separate database administration program for all but advanced database functions.Django can check if an entered password is correct by running it through the hash function and comparing the output to the stored hash value.Internally, while it provides choices for almost any functionality you might want (e.g. several popular databases, templating engines, etc.), it can also be extended to use other components if needed.

## Tech Stack Used
* HTML: Used for structuring the pages and presenting content to the user.
* CSS: For styling the platform, ensuring that it is user-friendly and responsive across devices.
* Python: The main programming language used to implement the system, taking advantage of its simplicity and the Django framework.
* Django Framework: A robust Python web framework used for both the frontend and backend development of the system.
* SQLite3: The default database system used in Django for data storage. It is lightweight and easy to set up, making it ideal for development and small to medium-sized projects.

## How It Works
User Registration: New users sign up by providing necessary details such as email, username, and password. Once registered, they can log in to the platform.<br /> <br />
Browse Cars: Users can view available cars for rent, sorted by model, type, or price.<br /> <br />
Rent a Car: Once a user finds a suitable vehicle, they can proceed to rent it. After the rental process is confirmed, the car is reserved for the user for the specified duration.<br /> <br />
Download Invoice: An invoice summarizing the rental details, including price, rental period, and car model, is automatically generated and can be downloaded.<br /> <br />
  
  ``
├── ousa_rental_system/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
├── cars/
│   ├── models.py (Car model, availability, pricing)
│   ├── views.py (Handles rental process, browsing)
│   ├── admin.py (Admin configurations for cars)
├── users/
│   ├── models.py (User profiles, authentication)
│   ├── views.py (Login, registration, profile management)
├── templates/
│   ├── index.html (Homepage)
│   ├── login.html (Login page)
│   ├── car_list.html (Car listings)
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
└── manage.py (Django's command-line utility)
``

# Aknowledgements
Django team for the excellent framework

All the tech students we worked with together in this project:<br /> <br />
Ousa Eddy Oliver                   
Nyongesa Jack Nyongesa      
Lister Kemuma Nyanchongi   
Stephanie Regina Kemunto 

## Installation : 

* Clone the repository
* Create Superuser (python manage.py createsuperuser) for accessing the admin portal
* Type python manage.py runserver and run the program
``

