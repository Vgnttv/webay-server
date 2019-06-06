# Webay

## [Check out the deployed version](https://webay.netlify.com/)

This repo contains a backend and uses Typescript, Express, routing-controllers and TypeORM

## Getting Started

### Postgres Database

Start a Postgres container using the following Docker command:

```bash
$ docker run \
  --rm \
  -e POSTGRES_PASSWORD=secret \
  -p 5432:5432 \
  postgres
```

### TypeStack Server

Then run `npm install` to install the dependencies.

Start the server with `npm start`
