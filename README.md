# Flaskr

The basic blog app built in the Flask [tutorial](https://flask.palletsprojects.com/tutorial/).

## Install

```bash
$ git clone https://github.com/hkbertoson/flask_tutorial
$ cd flask_tutorial
$ cd flask_tutorial
```

Create a virtualenv and activate it:

```bash
python3 -m venv .venv
. .venv/bin/activate
```

Or on Windows cmd:

```bash
py -3 -m venv .venv
.venv\Scripts\activate.bat
```

Install Flaskr:

```bash
pip install -e .
```

Or if you are using the main branch, install Flask from source before
installing Flaskr:

```bash
pip install -e ../..
pip install -e .
```

## Run

```bash
flask --app flaskr init-db
flask --app flaskr run --debug
```

Open http://127.0.0.1:5000 in a browser.

## Test

```bash
$ pip install '.[test]'
$ pytest
```

Run with coverage report:

```bash
$ coverage run -m pytest
$ coverage report
$ coverage html  # open htmlcov/index.html in a browser
```
