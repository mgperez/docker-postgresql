## Postgres

```shell
$ docker-compose config

# Rebuilder containers
$ docker-compose build

# Rerun containers
$ docker-compose up

$ docker inspect db-postgres -f "{{json .NetworkSettings.Networks }}"

# Shut down containers
$ docker-compose down -v --rmi all
```



### Starting the pgAdmin instance

[Local Development Set-Up of PostgreSQL with Docker](https://towardsdatascience.com/local-development-set-up-of-postgresql-with-docker-c022632f13ea)

The next step is to go to your web browser and type http://localhost:80.



### Test GraphQL API

Navigate to http://localhost:5433/graphiql to visualize the API GraphiQL documentation. From there you can execute queries and mutations such as the examples below. The API endpoint itself is http://0.0.0.0:5000/graphql.

[How to setup PostgreSQL + pgAdmin + PostGraphile in Docker](https://levelup.gitconnected.com/setup-postgresql-pgadmin-postgraphile-in-docker-d5bd1d97b17a)

[Docker-PostgreSQL-PostGraphile](https://github.com/alexisrolland/docker-postgresql-postgraphile)

