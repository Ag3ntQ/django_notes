# 🔍Django_Notes

# ☢️Error
- Time_Zone <a href="https://github.com/Ag3ntQ/Django_TimeZone_solution">Click here for solution</a>
# 📌Part 1
# 💡Start New project
- django-admin startproject <project_name>
<code> django-admin startproject todo</code>
# 💡 Create New App
<code>python manage.py startapp task</code>
- Here 'task' is app name 
- THEN Config app with settings.py
![CHEESE!](appconfig.jpg)
<code>INSTALLED_APPS =[
.... task.apps.TaskConfig,]</code>
- here 'tasks' is app name,apps,'TasksConfig' got from class name in "apps.py"
- and config app urls.py with project urls.py
# 💡Project urls.py
- <code>from django.urls import include</code>
- Add path in "urlpatterns= [ ]"
- <code>path('{option}',include('{app_name}.urls')</code>
# 💡Views.py
- <code>form django.http import HttpResponse</code>
- HttpRsponce for 'text-response'</br>
<code>return HttpResponce("Hello World")</code>
- render - mapping file</br>
<code>return render(request,"index.html")</code>
# 💡 Templates
- html file save in app/templates
- <a href="https://docs.djangoproject.com/en/4.0/ref/templates/language/">Template language</a>
# 💡 Local hosting
- Start a local web server
- <code>python manage.py runserver 8000</code>
# 📌Part 2
# 💡models.py

