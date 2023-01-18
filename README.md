# DJANGO 4: FROM DEVELOPMENT TO DEPLOYMENT

Free and open source back-end framework.

```Free:``` ```It can be used to build commercial grade applications without any cost.```

```Open source:``` ```Source code is available publicly.```

```Back-end:``` ```Responsible to program the servers, cannot decide the user interface of your website in the front-end.```

```Framework:``` ```Collection of components which allows us to build sites faster.```

```Django provides an admin panel.```

# Client server architecture.
A website/web application resides on a server.To access a website, we make a URL request from our browser (client) to the server.
The server needs to be able to handle incoming URL request and return some appropriate response.
This response might be some plain simple data, or it might be an entire webpage.This webpage is then returned to the client( browser).



# Prerequisites

      1)Visual Studio Code
      2)Python IDLE
      3)Node JS


# Packages required be pre-installed.

#### STEP:1
Install latest version of python on your machine.
#### STEP:2
* Install the Virtual environment.

      pip install virtualenv

* Create a folder```(djangopro)```in your machine.
      
      cd djangopro
      virtualenv env
      
* Now go to folder```Scripts``in the env and activate the virtual environment.

      cd env
      cd Scripts
      activate
      
* If we want to deactivate the virtual environment.

      deactivate
      

#### STEP:3
* Go back to the original directory.

      cd..

* Create a Django Project.

      pip install django==4.0
      django-admin startproject mysite
      cd mysite
 
* Connecting to the local server.

      python manage.py runserver
      
* Creating a database

      python manage.py startapp myapp
      
* Creating a database

      python manage.py makemigrations
      python manage.py migrate
 

 [DEMO VIDEO](https://drive.google.com/file/d/1E3pU-TO777645haBH0O75Tc2pxdVLCVE/view?usp=sharing)


