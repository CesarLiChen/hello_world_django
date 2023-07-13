# A Hello World project with Django.  

**Using this README as a way to document commands learned.**  

- `python3 --version`  
- `sudo apt install python3-pip`  
- `sudo apt install python3-venv`  

## Virtual environment (venv) commands.  

- `python3 -m venv .venv`  *creates virtual environment named .venv.*
- `source .venv/bin/activate`  *activates venv.*
- `deactivate`  *deactivates venv, yes, just that word alone.*

## Django portion  

**Make sure to activate the venv BEFORE running the commands below.**  
- `python3 -m pip install django`  
- `python3 -m django --version`
- EXTRA `pip list --local` *lists installed packages in venv.*  
&nbsp; 
  - `python3 manage.py makemigrations` *creates but does **NOT** apply migrations to installed applications.*
  - `python3 manage.py migrate` *actually applies migrations to database.*  
    :arrow_up_small: **The commands above should be ran everytime the models change in a way that will affect the structure of the data.**  
&nbsp;
- `django-admin startproject web_project .` *creates Django project.*
- `python3 manage.py startapp <APP_NAME>` *creates an application that contains models, views, etc.*
- `python3 manage.py runserver` *starts Django's development server.*  
- `Ctrl-C` *to stop server.*  
- `python3 manage.py startapp hello` *creates Django app called hello.*  

## Docker portion  

- `docker` *list commands available.*  
- `docker <COMMAND> --help` *specific help.*  
- `docker image ls --all` *lists images on machine only.*  
- `docker container ls --all` or `docker ps -a` *lists all containers on machine, `-a` flag shows non-running containers*
