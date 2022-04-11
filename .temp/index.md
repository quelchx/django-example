# In order to create a virtualenv for django I had to

- ensure latest python version is installed
- ensure pip is installed
- use the wsl2 terminal
- `pip install virtualenv`
- if they're problems run `pip3 uninstall virtualenv` then re run `pip install virtual env`
- once installed run `virtualenv env`
- cd into env/bin then run `. activate`
- to exit to virtualenv run `deactivate`

## Next Step: Install Django

- run `pip install django`
- run `django-admin` to verify django is installed
- run `django-admin startproject projectname` to create a project

- To run the server `cd projectname` then `python manage.py runserver`
- This will run a basic template -- afterwords we can run `python manage.py startapp base` note: base can be named whatever

- To start working with a database run `python manage.py migrate`

- To make migrations run `python manage.py makemigrations` then run `python manage.py migrate`
- To create a admin level user run `python manage.py createsuperuser` then follow the steps that prompt
