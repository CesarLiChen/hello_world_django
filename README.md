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

- `python3 -m pip install django`  
- `python3 -m django --version`  
- `django-admin startproject web_project .` *creates Django project.*  
- `python3 manage.py runserver` *starts Django's development server.*  
- `Ctrl-C` *to stop server.*  
- `python3 manage.py startapp hello` *creates Django app called hello.*  

## Docker portion  

- `docker` *list commands available.*  
- `docker <COMMAND> --help` *specific help.*  
- `docker image ls --all` *lists images on machine only.*  
- `docker container ls --all` or `docker ps -a` *lists all containers on machine, `-a` flag shows non-running containers*
