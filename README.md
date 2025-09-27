## Getting Started:

1. First, add .env.dev in root folder:

```bash
DEBUG=1
SECRET_KEY=
DJANGO_ALLOWED_HOSTS=localhost 127.0.0.1 [::1]
SQL_ENGINE=django.db.backends.postgresql
SQL_DATABASE=djangobnb
SQL_USER=postgresuser
SQL_PASSWORD=postgrespassword
SQL_HOST=db
SQL_PORT=5432
DATABASE=postgres
```

2. Activiate environment.
3. Run in root folder, to start the server in background:

```bash
docker-compose up --build -d
```