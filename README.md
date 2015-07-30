# InstalandoDjango
Instalando Django no Ubuntu

###Instalação do Django 1.8 - Passo a Passo:
####Parte 1 - Instale o PIP:
>PIP para python 2.7: `sudo apt-get install python-pip`

>PIP para python 3.4: `sudo apt-get install python3-pip`

####Parte 2  - Instale o virtualenv:
>Para instalar: `sudo apt-get install python-virtualenv`

>Para ativar o ambiente virtual entre na pasta criada do ambiente e digite o comando: `source bin/activate`

>Para desativar o ambiente virtual, digite `deactivate`

####Parte 3  - Instale o django:
IMPORTANTE: Ative o ambiente virtual *antes* de iniciar os comandos abaixo:

>Para instalar a última versão: `pip install django`

>Para instalar outra versão: `pip install django==<versão>`

####Parte 4 - Para criar o Projeto, utilize os comandos a seguir:
>Para criar o projeto: `django-admin.py startproject <nome_do_projeto>`

####Parte 5 - Para iniciar o Projeto
Entre na pasta do projeto, criada dentro do seu ambiente virtual.

>Para criar as primeiras tabelas: `python manage.py migrate`

>Para criar o primeiro usuario (administrador): `python manage.py createsuperuser`

>Para rodar o servidor web: `python manage.py runserver`

