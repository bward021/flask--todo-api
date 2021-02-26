# Flask TODO API

## Dependency Docs
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
- [Flask Marshmallow](https://flask-marshmallow.readthedocs.io/en/latest/)
- [Marshmallow-sqlalchemy](https://marshmallow-sqlalchemy.readthedocs.io/en/latest/)
- [flask-cors](https://flask-cors.readthedocs.io/en/latest/)


## How to start Server
```
$ pipenv shell
$ python app.py
```


## How to create the database
```
$ pipenv shell
$ python
>>> from app import db
>>> db.create_all()
