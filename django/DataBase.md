## 🛠️ Start DataBase :-

<h3 align="center"> SQLite </h3>

`Step 1` : Settings.

```
DATABASES = {
    "default": {
        "ENGINE": "django.db.backends.sqlite3",
        "NAME": BASE_DIR / "db.sqlite3",
    }
}
```

<h3 align="center"> PostgreSQL </h3>

`Step 1` : Create Database.

```
su - postgres
```

```
psql
```

```
CREATE USER django_proj WITH PASSWORD 'django@@1';
```

```
create database homeverse;
```

```
\c homeverse
```

```
GRANT ALL PRIVILEGES ON DATABASE homeverse TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL SEQUENCES IN SCHEMA public TO django_proj;
```

`Step 2` : Settings.

```

```

<h3 align="center"> MySQL </h3>

`Step 1` : Settings.

```
DATABASES = {
    "default": {
        # Database mysql
        "ENGINE": "django.db.backends.mysql",
        "NAME": "devdepo_fastr",
        "USER": "devdepo_fastr",
        "PASSWORD": "Dep0WebEG$",
        "HOST": "localhost",
        "PORT": "3306",
    }
}
```

`Step 2` : Create Database.

```
new
```

```
devdepo_fastr
```

```
Dep0WebEG$
```

```
grant all PRIVILEGES on devdepo_fastr.* to devdepo_fastr@'%' identified by "Dep0WebEG$" with GRANT option
```

```
go
```

`Step 3` : MySQL CPanel.

```
backdepo_faster
```

```
T{l.zNj#dfZV
```
