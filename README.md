# Mini_Django_v1
Step 1: create directory mkdir <project-root>
Step 2: cd to directory in step 1
Step 3: django-admin.exe startproject velocity
Step 4: cd velocity
Step 5: create DB tables python manage.py migrate
Step 6: run project python manage.py runserver
Step 7: create app => python manage.py startapp blog
Step 8: Inform django we have created new app by appending app name to the INSTALLED_APPS list in settings.py
Step 9: Let django know that we have created new model python manage.py makemigrations blog
Step 10: migrate DB python manage.py migrate
Step 11: Register newly created model on admin interface using admin.py
Step 12: Create user and password using python manage.py createsuperuser
Step 13: Run application python manage.py runserver and check admin interface by heading to /admin
