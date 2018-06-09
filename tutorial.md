# install Django
pip install Django==2.0.6

# create a project
django-admin.py startproject Django

# edit settings.py
TIME_ZONE = 'Asia/Taipei'
USE_TZ = False

# create or update databased
py manage.py migrate

# run server
visit http://127.0.0.1:8000/ 

# create a model
manage.py startapp news