# stacks_db

```
cp .env.example .env

docker-compose up -d
```
# MySQL
Para modificar el user/pass de MySQL modificar las keys en el archivo `.env`
```
MYSQL_USER
MYSQL_ROOT_PASSWORD

```
El puerto al que se expone a la red se cambia modificando la key
```
MYSQL_PORT
```

# Mongo
Para modificar el user/pass de Mongo modificar las keys en el archivo `.env`
```
MONGO_INITDB_ROOT_USERNAME
MONGO_INITDB_ROOT_PASSWORD
```
El puerto al que se expone a la red se cambia modificando la key
```
MONGO_PORT
```

# Postgres
Para modificar el user/pass de Mongo  modificar las keys en el archivo `.env`
```
POSTGRES_PASSWORD
POSTGRES_USER
```
El puerto al que se expone a la red se cambia modificando la key
```
POSTGRES_PORT
```





