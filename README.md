## Getting Started:

1. First, add .env.dev in root folder:
DEBUG=1
SECRET_KEY='django-insecure-=y%2d!gk9q%(do6&o6id&eersa)hj681-nkqrrmx@rmr^uvva2'
DJANGO_ALLOWED_HOSTS=localhost 127.0.0.1 [::1]
SQL_ENGINE=django.db.backends.postgresql
SQL_DATABASE=djangobnb
SQL_USER=postgresuser
SQL_PASSWORD=postgrespassword
SQL_HOST=db
SQL_PORT=5432
DATABASE=postgres

2. Activiate environment.
3. Run in root folder, to start the server in background:

```bash
docker-compose up --build -d
```