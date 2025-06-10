# django-templates-e-boas-praticas
aula 01 de django

Antes de começar:

1 - ter o pip:
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py

2 - ter o virtualenv:
pip install virtualenv

Depois dentro da pasta:
1 - instalar o virtualven
python -m virtualenv venv

e ativar:
venv/Scripts/activate   <- Ativa
deactivate              <- Desativa

2 - instalar o Django
pip install django

3 - e criar o projeto:
django-admin startproject setup .

Para rodar o servidor pela primeira vez:
python manage.py runserver

=====

4 - foi instalado dotenv:
pip install python-dotenv

-> Para atualizar tudo q foi instalado no ambiente de trabalho:
pip freeze > requirements.txt 
