# Warbler
Twitter clone built with Flask, WTForms, PostgresSQL and Flask SQLAlchemy.


## Setup

Create Python virtual environment:
```
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Setup database and populate:
```
(venv) $ createdb warbler
(venv) $ python seed.py
```

Start server:
```
(venv) $ flask run
```

Open http://localhost:5000/ to view project in the browser.

## Built With
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
* [WTForms](https://wtforms.readthedocs.io/en/2.3.x/)
* [PostgresSQL](https://www.postgresql.org/)
* [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [Twitter Bootstrap](https://getbootstrap.com/)