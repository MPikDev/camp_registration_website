# camp_registration_website
A django website for registering, receiving payment through PayPal, and sending email notifications for camp.

# To get the website running on a windows machine 
1. apt-get update
1. apt-get install gcc
1. apt-get install redis-server
1. apt-get install python python-dev python-setuptools
1. easy_install pip
1. pip install -U pip
1. pip install virtualenv
1. virtualenv venv 
1. . venv/bin/activate 
1. pip install -r requirements.txt
1. python manage.py rumserver
1. ctrl c 
1. python manage.py makemigrations 
1. python manage.py migrate 
1. python manage.py createsuperuser
1. python manage.py rumserver
