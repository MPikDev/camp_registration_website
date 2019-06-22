# camp_registration_website
A django website for registering, receiving payment through PayPal, and sending email notifications for camp.

# Things to Install
1. Install from link [python 2.7](https://www.python.org/ftp/python/2.7.16/python-2.7.16.amd64.msi)
1. Add to Environment Variables the Path C:\Python27 [tutorial](https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/)
1. Downlaod pip 
    1.command line way: curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
    1. [tutorial](https://www.liquidweb.com/kb/install-pip-windows/)
1. Install pip
    1. cmd line: python get-pip.py
1. Add to Environment Variables the path C:\Python27\Scripts (same way as above)

# To get the website running on a windows machine
1. pip install virtualenv
1. get a clone of the repo if not already then go into the camp_registration_website directory
1. virtualenv venv 
1. venv\Scripts\activate 
1. pip install -r requirements.txt
1. in personal_code directory the local_settings_copy remove the _copy from the file name
1. python manage.py runserver
1. ctrl c 
1. python manage.py makemigrations 
1. python manage.py migrate 
1. python manage.py createsuperuser `remember the username and password`
1. python manage.py runserver
