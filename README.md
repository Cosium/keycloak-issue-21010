# Performance issues when a realm contains ~8700 clients on version 21.1.1 with Postgres

https://github.com/keycloak/keycloak/issues/21010

# Postgres deployment

```shell
$ docker run --name keycloak-postgres -p 5432:5432 -e POSTGRES_PASSWORD=password postgres
```

