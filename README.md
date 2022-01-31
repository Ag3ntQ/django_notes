# Django_Notes
# Project Todo

# Start project 
- django-admin startproject <project_name>
- django-admin startproject todo

# New App
- python manage.py startapp day ( day is app name )
- Config with settings.py
   - INSTALLED_APPS =[ day.apps.DayConfig, ]
- config app urls.py with project urls.py
# Project urls.py
- from django.urls import include
- - path('{option}',include('{app_name}.urls')
# Views.py
- form django.http import HttpResponse 


