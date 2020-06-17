# DUBLIN_INTERCOM
Install virtual enviroment with python3

Configure your virtual environment with file included in repo

mkdir virtual

cd virtual

virtualenv -p python3.

start virtual enviroment

source virtual/bin/activate


pip install -r requirements.txt

To import JSON values ---    python manage.py import_from_json_file

Initialize db.sqlite3 database

python manage.py migrate


Create database superuser

python manage.py createsuperuser

Start server

python manage.py runserver


requirements.txt

ertifi==2019.3.9

chardet==3.0.4

Django==2.1.7

djangorestframework==3.9.1

idna==2.8

pycodestyle==2.5.0

pytz==2018.9

requests==2.21.0

urllib3==1.24.1


