# graphql-demo

## Start docker for postgres
```
docker run --rm  --name pg-docker -e POSTGRES_PASSWORD=docker -d -p 5432:5432 -v $HOME/docker/volumes/postgres:/var/lib/postgresql/data postgres
```

## GraphiQL
http://localhost:8099/graphiql
