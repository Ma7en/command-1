## 🛠️ Start Code Email :-

<h3 align="center"> SMTP Email </h3>

`Code 1` : # SMTP google

```
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "smtp.gmail.com"
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = "m9ee9m@gmail.com"
DEFAULT_FROM_EMAIL = EMAIL_HOST_USER
FROM_EMAIL = "m9ee9m@gmail.com"
EMAIL_HOST_PASSWORD = "mpqxfsllvcoldawc"
```

`Code 2` : # SMTP localhost

```
Download program for windows
https://github.com/mailhog/MailHog/releases
```

```
Download program for Ubuntu
wget https://github.com/mailhog/MailHog/releases/download/v1.0.1/MailHog_linux_amd64
mv MailHog_linux_amd64 MailHog
chmod +x MailHog
```

```
Run Program
./MailHog
```

```
Open Link
http://localhost:8025
```

```
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "localhost"
EMAIL_PORT = 1025
DEFAULT_FROM_EMAIL = "no-reply@localhost"
FROM_EMAIL = "no-reply@localhost"
EMAIL_HOST_USER = "no-reply@localhost"
```
