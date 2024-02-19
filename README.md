# Python Flask Authentication

This repository contains the code used in the Python Flask Authentication


### Cloning the Repository

    git clone https://github.com/evadelzz1/flask_login1.git

### Setting up a Virtual Environment

    cd ./flask_login1

    pyenv versions

    pyenv local 3.11.6

    pyenv versions

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore

### Activate the virtual environment

    python -m venv .venv && source .venv/bin/activate

### Install the required dependencies

    pip list

    pip install -r requirements.txt

    # create database

    python

    >>> from app import app,db
    >>> app.app_context().push()
    >>> db.create_all()
    >>>
    >>> exit()


### Running the Application

    python app.py

### Deactivate the virtual environment

    deactivate

## Reference

[Python Flask Authentication Tutorial - Learn Flask Login](https://www.youtube.com/watch?v=71EU8gnZqZQ)
[github](https://github.com/arpanneupane19/Python-Flask-Authentication-Tutorial)

[Flask-SQLAlchemy 사용해보기](https://kimjingo.tistory.com/116)
[Flask-SQLAlchemy db.create_all() raises RuntimeError](https://stackoverflow.com/questions/73961938/flask-sqlalchemy-db-create-all-raises-runtimeerror-working-outside-of-applicat)
