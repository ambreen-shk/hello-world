# hello-world
In-process
To create a new application run, $ python manage.py startapp <appname>, where <appname> is the name of the application you wish to create.
Tell your Django project about the new application by adding it to the INSTALLED_APPS tuple in your project’s settings.py file.
In your project urls.py file, add a mapping to the application.
In your application’s directory, create a urls.py file to direct incoming URL strings to views.
In your application’s view.py, create the required views ensuring that they return a HttpResponse object.
