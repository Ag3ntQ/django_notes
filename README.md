# 🔍Django_Notes
# 📑Project Todo

# ☢️Error
- Time_Zone <a href="https://github.com/Ag3ntQ/Django_TimeZone_solution">Click here for solution</a>
# 💡Start project 
- django-admin startproject <project_name>
- django-admin startproject todo

# 💡New App
- python manage.py startapp day ( day is app name )
- Config with settings.py
   - INSTALLED_APPS =[ day.apps.DayConfig, ]
- config app urls.py with project urls.py
# 💡Project urls.py
- from django.urls import include
- - path('{option}',include('{app_name}.urls')
# 💡Views.py
- form django.http import HttpResponse
- def index(request):</br>
  return HttpResponce("Hello World")
- def todopage(request):</br>
  return render(request,"index.html")
# 💡 Templates
- html file => app/templates
- <a href="https://docs.djangoproject.com/en/4.0/ref/templates/language/">Template language</a>

     


