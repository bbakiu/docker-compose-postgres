# How to use Postgres with Docker Compose and DBeaver

## Suposing you have already installed docker compose run:
```
docker-compose up --build
```

This will startup a database instance with the provide username, password and database name.

## To connect to this instance in DBeaver:
1. Open DBeaver.
2. Choose on the top left corner the New Database Connection Icon, or from Database Menu select New Database Connection.
3. Select PostgreSQL and fill in the credentials.
4. Now you should see the database on the left panel, and be able to run queries on it.