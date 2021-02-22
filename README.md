<p align="center">
  <a href="http://nestjs.com/" target="blank">
    <img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" />
  </a>
</p>

# Nest.js + MongoDB + Docker Starter

This is starter project for Nest.js, MongoDB and Docker. You can easily start your production ready containered project by forking this repo.

## How to use

Install dependencies

```bash
$ npm install
```

Run docker container in development mode

```bash
$ npm run docker:dev
```

or

```bash
$ docker-compose up
```

Create and run docker container on production

```bash
$ docker build -t app-name . && docker run app-name -p 8080:3000
```

## Running the app without Docker and MongoDB

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
## Learn more

- [Nest.js Framework](https://nestjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/)

## License

This project is [MIT licensed](LICENSE).
