Setup for different projects:

Git:
1. Create Repo
2. Add Gitignore


Virtual Environment
Use the conda virtual environment
1. conda search "^python$"
2. conda create -n $ENVIRONMENT_NAME python=x.x
3. source activate $ENVIRONMENT_NAME

When ready to switch out
4. source deactivate


Set up for Django
1. django-admin startproject mysite
2. python manage.py startapp polls
python manage.py check;
$ python manage.py makemigrations polls
python manage.py sqlmigrate polls 0001
3. python manage.py migrate
4. python manage.py runserver


Set up superusers
$ python manage.py createsuperuser



Run Django Shell
$ python manage.py shell
