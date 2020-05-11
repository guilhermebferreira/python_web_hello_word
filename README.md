# python_web_hello_word
Apenas um hello word demonstrativo com Django e Flask, para fins didaticos


## Flask

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