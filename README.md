
## Setup

Virtual env

```bash
$ python -m venv env

$ source env/bin/activate
```

Update pip and install dependencies

```bash
$ python -m pip install --upgrade pip

$ python -m pip install -r requirements.txt
```

Migrate the database

```bash
$ cd mysite/

$ python manage.py migrate
```

Start the development server

```bash
$ python manage.py runserver
```
