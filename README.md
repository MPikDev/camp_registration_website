# camp_registration_website
A django website for registering, receiving payment through PayPal, and sending email notifications for camp.

# things to install
1. https://www.python.org/ftp/python/2.7.16/python-2.7.16.amd64.msi
1. add to Environment Variables path C:\Python27   https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/
1. get pip cmd line
    1. curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
1. python get-pip.py
1. add to Environment Variables path C:\Python27\Scripts

# To get the website running on a windows machine
1. pip install virtualenv
1. virtualenv venv 
1. venv\Scripts\activate 
1. pip install -r requirements.txt
1. python manage.py rumserver
1. ctrl c 
1. python manage.py makemigrations 
1. python manage.py migrate 
1. python manage.py createsuperuser
1. python manage.py rumserver
