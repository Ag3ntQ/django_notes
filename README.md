# 🔍Django_Notes
# 📑Project Todo

# ☢️Error
- Time_Zone <a href="https://github.com/Ag3ntQ/Django_TimeZone_solution">Click here for solution</a>
# 📌Part 1
# 💡Start New project
- django-admin startproject <project_name>
<code> django-admin startproject todo</code>
# 💡 Create New App
<code>python manage.py startapp day</code>
- Here 'day' is app name 
- THEN Config app with settings.py
<code>INSTALLED_APPS =[
.... day.apps.DayConfig,]</code>
- here 'day' is app name,apps,'DayConfig' got from class name in "apps.py"
- and config app urls.py with project urls.py
# 💡Project urls.py
- <code>from django.urls import include</code>
- Add path in "urlpatterns= [ ]"
- <code>path('{option}',include('{app_name}.urls')</code>
# 💡Views.py
- form django.http import HttpResponse
- def index(request):</br>
  return HttpResponce("Hello World")
- def todopage(request):</br>
  return render(request,"index.html")
# 💡 Templates
- html file => app/templates
- <a href="https://docs.djangoproject.com/en/4.0/ref/templates/language/">Template language</a>
   


