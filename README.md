Docker rancher
===

Install and run rancher with docker-compose with :
- nginx
- mysql

You need to have in .env, theses variables below:
```
CATTLE_DB_CATTLE_MYSQL_HOST
CATTLE_DB_CATTLE_MYSQL_NAME
CATTLE_DB_CATTLE_USERNAME
CATTLE_DB_CATTLE_MYSQL_PORT
CATTLE_DB_CATTLE_PASSWOR
MYSQL_ROOT_PASSWORD
MYSQL_DATABASE
MYSQL_USER
RANCHER_VERSION
DB_VOLUME
```

To run rancher :
```
docker-compose up -d
```
