# backend_fastapi
## Setup
To run this project, install it locally using poetry:
```
$ pip install poetry (or pip3 install poetry)
```
```
$ poetry install (to install dependences)
```
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
