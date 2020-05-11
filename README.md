# python_web_hello_word
Apenas um hello word demonstrativo com Django e Flask, para fins didaticos

### Install

Presumindo que o python3 já esteja devidamente instalado

#### Instalando pip3
    sudo apt-get install python3-pip python3-dev


#### Instalando virtualenv
    pip3 install virtualenv



## Flask

    cd flask

##### Criando o virtualenv

    virtualenv -p python3 venv
    
    
##### Ativando-o
    
    . venv/bin/activate
    
##### Instalando o flask dentro do virtualenv
    
    pip install Flask


##### Exportando como variavel de ambiente o nome do arquivo principal do seu projeto

    export FLASK_APP=app.py

##### Rodando

    python -m flask run
ou

    flask run
ou

    flask run --host=0.0.0.0
    

## Django

    cd django
    
##### Criando o virtualenv

    virtualenv -p python3 venv
    
    
##### Ativando-o
    
    . venv/bin/activate
    
    
##### Aplicando as migrations no banco de dados
No caso, são os models do django-admin
    
    ./manage.py migrate
    
    
##### Rodando

    ./manage.py runserver
    
ou
    
    ./manage.py runserver localhost:1111



### Desativando o virtualenv

    deactivate

