### instalar Django

    pip install django

### ou

    python3 -m pip install Django


### para criar um projeto novo no django:

    django-admin startproject "nome do projeto aqui"

### para popular banco de dados:

    python3 manage.py migrate

### para criar super user:

    python3 manage.py createsuperuser

## na pasta do projeto crie um arquivo com o nome views.py


### agora crie um app no projeto:

    python3 manage.py startapp "nome do app aqui"

### agora você precisa registrar seu app em settings.py:

![djangoapp](https://user-images.githubusercontent.com/79322362/155889452-a529e62f-85b5-471d-9f42-6342a345dde1.png)
