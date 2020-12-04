# backend_fastapi
## Setup
To run this project, install it locally using poetry:
```
$ pip install poetry (or pip3 install poetry)
```
### To install dependences
```
$ poetry install (to install dependences)
```
### To create a virtualenv(.venv)
```
$ poetry shell 
```
```
$ docker-compose up -d
```
```
$ docker-compose up -d db
```
```
$ docker-compose up -d app
```
### From ```backend``` cd app (container of alembic.ini)
```
$ alembic upgrade head
```
```
$uvicorn main:app --reload
```
