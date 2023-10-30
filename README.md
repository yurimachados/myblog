# myblog
Django Personal Blog


## Deploy

1. Install virtual environment
```
python -m venv venv
```

2. Ativate virtual enviroment 

2.1. windows
```
source venv/scripts/activate
```
2.2. linux
```
source venv/bin/activate
```

3. Install requirements
```
pip install -r requirements.txt
```

4. Change the name of the file `.env.example` to `.env`

5. Migrate
```
python manage.py makemigrations
```
```
python manage.py migrate
```

6. Run server
```
python manage.py runserver
```