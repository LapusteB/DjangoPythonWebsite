# DjangoPythonWebsite

So, This is my framework for the front end of an application I have created through Django. "Thrive"

I started off by downloading Django and creating a virtual environment for my manage.py library.
From there I used a bootstrap HTML template to incorporate an index.html website and get my feet wet with how Django works.

Since I have not done any back end work for this app, I have not posted it on a cloud or hard server.
It is simply run on my machine at http://127.0.0.1:8000/

by accessing the local files and activation the virutal environment I am able to make real time changes to the front end of the app.
activating the website using windows PowerShell:

PS C:\Users\Brian S. Lapuste> cd dev
PS C:\Users\Brian S. Lapuste\dev> ls


    Directory: C:\Users\Brian S. Lapuste\dev


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        11/8/2020   7:55 PM                django-website


PS C:\Users\Brian S. Lapuste\dev> cd django-website
PS C:\Users\Brian S. Lapuste\dev\django-website> env\scripts\activate
(env) PS C:\Users\Brian S. Lapuste\dev\django-website> ls


    Directory: C:\Users\Brian S. Lapuste\dev\django-website


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----         1/9/2021   4:34 AM                djangoapp
d-----        11/8/2020   7:47 PM                env


(env) PS C:\Users\Brian S. Lapuste\dev\django-website> cd djangoapp
(env) PS C:\Users\Brian S. Lapuste\dev\django-website\djangoapp> python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
January 09, 2021 - 04:36:12
Django version 3.1.3, using settings 'djangoapp.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
