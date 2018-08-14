# Deploying-Linux-Servers

-Project URL http://54.93.105.64
-IP Address 54.93.105.64 
-Port 2200  
-grader username: grader  

# List of packages installed
-Apache
-mod_wsgi
-PostgreSQL
-Flask (0.12.2)  
-Flask-WTF (0.14.2)  
-httplib2 (0.10.3)  
-certifi (2017.4.17)
-chardet (3.0.4)  
-click (6.7)  
-idna (2.5)  
-itsdangerous (0.24)  
-Jinja2 (2.9.6)  
-MarkupSafe (1.0)  
-oauth2client (4.1.2)  
-pip (9.0.1)  
-pip-autoremove (0.9.0)  
-psycopg2 (2.7.1)  
-pyasn1 (0.2.3)  
-pyasn1-modules (0.0.9)  
-requests (2.18.1)  
-rsa (3.4.2)  
-setuptools (20.7.0)  
-six (1.10.0)  
-SQLAlchemy (1.1.11)  
-urllib3 (1.21.1)  
-virtualenv (15.1.0)  
-Werkzeug (0.12.2)  
-wheel (0.29.0)  
-WTForms (2.1)  
-yolk (0.4.3)  

# Configuration Changes

Changed Server time to UTC  
Change the SSH port from 22 to 2200  
Configured UFW to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).  

#The Project

1) This project is part of of my FSND program at Udacity. 
2) It is designed in such a way as to solve actual challenges here in Kenya
3) It is a catalog of skilled workers and technicians in Nairobi by location. When you open tha application, you get 
    workers near you whom you can filter by the specific skill you require
4) In a time of on demand services in the gig economy, such a platform is handy to match skills required with people who need such services

# The Back End

1) The software is written in Python using Flask Framework
2) It uses PostgresSQL to store data
3) It uses Oauth to authenticate users via google and facebook sign in

# The Front End

1) The front end is written in HTML5 and utilizes bootstrap for styling and knockout js to manipulate the DOM
2) The project further uses google maps API to display location of workers on a map and displays some related tips from articles from the New York Times

# Hosting
1) The Application is Hosted on an Amazon lightsail account running on Ubuntu
