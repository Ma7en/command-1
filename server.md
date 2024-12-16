## 🛠️ Start Superuser :-

<h3 align="center"> Run Prject On Server </h3>

`Step 1` : Run Server localhost.

```
python manage.py runserver
```

```
python3 manage.py runserver
```

`Step 2` : Run Server.

```
ifconfig
```

```
python manage.py runserver 192.168.1.20:8000
```

`step 3` : Run Server daphne.

```
daphne -b 127.0.0.1 -p 8000 sampleProject.asgi:application
```

`step 4` : Run Redis Server.

```
pkill redis-server
```

```
redis-server --port 6380
```

```
celery -A proj worker -l INFO
```
