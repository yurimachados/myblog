# myblog
Django Personal Blog


## Deploy

Install virtual environment
```
python -m venv venv
```

Ativate virtual enviroment windows
```
source venv/scripts/activate
```

Ativate virtual enviroment linux
```
source venv/bin/activate
```

Install requirements
```
pip install -r requirements.txt
```

Change the name of the file `.env.example` to `.env`

Migrate
```
python manage.py makemigrations
```
```
python manage.py migrate
```

Run server
```
python manage.py runserver
```