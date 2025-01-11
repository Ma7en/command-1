## 🛠️ Start Superuser :-

<h3 align="center"> Run Prject On Server </h3>

`step 0` : deactivate venv

```
deactivate
```

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

`step 5` : cpanel

```
https://back.depowebeg.com/cpanel
```

```
backdepo
```

```
_uFyW=ru(H,D
```

`step 6` : the-faster

```
https://faster.back.depowebeg.com/
```

`step 7` : otp-server for ubuntu

# step 1:

wget https://github.com/mailhog/MailHog/releases/download/v1.0.1/MailHog_linux_amd64
mv MailHog_linux_amd64 MailHog
chmod +x MailHog

# step 2:

./MailHog

# step 3:

# -> settings.py

EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "localhost"
EMAIL_PORT = 1025
DEFAULT_FROM_EMAIL = "no-reply@localhost"

# step 4:

http://localhost:8025

`step 8` : otp-server for windows

# step 1:

https://github.com/mailhog/MailHog/releases

# step 3:

# -> settings.py

EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "localhost"
EMAIL_PORT = 1025
DEFAULT_FROM_EMAIL = "no-reply@localhost"

# step 4:

http://localhost:8025
