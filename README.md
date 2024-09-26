# Ousa Car Rental System
This is a Car rental system implemented using Django FrameWork.<br /> <br />
User can login then rent a car<br /> <br /> 
User can also download the bill generated.

About Django : 
Django is an MVT web framework that is used to build web applications.Django has an in-built administration interface which lets you handle your models, user/ group permissions and to manage users. With model interface in place, there is no need for a separate database administration program for all but advanced database functions.Django can check if an entered password is correct by running it through the hash function and comparing the output to the stored hash value.Internally, while it provides choices for almost any functionality you might want (e.g. several popular databases, templating engines, etc.), it can also be extended to use other components if needed.

## Tech Stack Used
* HTML: Used for structuring the pages and presenting content to the user.
* CSS: For styling the platform, ensuring that it is user-friendly and responsive across devices.
* Python: The main programming language used to implement the system, taking advantage of its simplicity and the Django framework.
* Django Framework: A robust Python web framework used for both the frontend and backend development of the system.
* SQLite3: The default database system used in Django for data storage. It is lightweight and easy to set up, making it ideal for development and small to medium-sized projects.
  
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

