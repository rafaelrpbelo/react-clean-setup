# About

Clean setup for React app.

- React version: 17.0.2
- Builder: Webpack (5.53)
- Extra:
  - Sass (.scss) - v12.1.0
  - Html webpack plugin - v5.3.2
  - Webpack dev server - v.4.2.1

## Requirements

- Node.js - v14.17.6
- yarn - v1.22.5

## Running

```shell
$ yarn install
$ yarn dev
```

Go to [http://localhost:8080](http://localhost:8080)

## Running with Docker

```shell
$ cp docker-compose.yml{.sample,}
$ docker-compose run --rm web yarn install
$ docker-compose build
$ docker-compose up web
```

Go to [http://localhost:8080](http://localhost:8080)

## Building production bundle

```shell
$ yarn install
$ yarn build
```
