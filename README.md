# Demo 1 for django crud with my sql

# Rest api for django rest framwork

## Demo1/Emplolee
django crud with my sql

## Installation

1.Clone the project using git hub
2. Demo1/employee/
In console 
For mysql 
“pip install mysqlclient”

If not work you need add mysqlclint manually 

Download & Install MYSQLCLIENT For Python : https://www.lfd.uci.edu/~gohlke/pytho...

Go to this site choose your django app version download and unzip
Pip install mysqlclient your download location/mysqlclient-1.4.6-cp38-cp38-win32.whl
Press enter


Then need to change setting.py

DATABASES = {

'default': {

'ENGINE': 'django.db.backends.mysql',

'NAME': databasename',

'USER': 'dbname',

'PASSWORD': 'dbpassword',

'HOST': 'localhost'

}

}


“Python manage.py migrate” for database migration



3.For the forms used in framworks

“pip install django-crispy-forms”

Demo1/employee/setting.py
INSTALLED_APPS = [


'employee',

'crispy_forms'

]




4. run servser “python manage.py runserver”




