# Dev set up

- install `hasura-cli` from https://docs.hasura.io/1.0/graphql/manual/hasura-cli/install-hasura-cli.html#install-hasura-cli
- `docker-compose up` will start the database and hasura server
- `hasura migrate apply` to apply migrations to local db
- `hasura console` to connect to the server
- any changes made to the database structures or hasura metadata will be saved in `migrations/`
- commit this repo semi-regularly to commit those migrations

# Staging/prod setup

- TODO

