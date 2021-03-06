<h1 align="center">Welcome to nestjs-starter 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="localhost:8080" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="#" target="_blank">
    <img alt="License: UNLICENSED" src="https://img.shields.io/badge/License-UNLICENSED-yellow.svg" />
  </a>
</p>

> A starter kit for building NestJS REST APIs

## Features

This repository demonstrates example usages of the following concepts in NestJS:

- JWT Authentication via Passport
- Controllers
- Providers
- Modules
- TypeORM 
- Basic testing
- Configuration
- Logging
- Swagger/OpenAPI
- Compodoc

## Install

```sh
npm install
```

## Running Locally

Ensure that you have a .env file setup at the root of the project. See the `.env-example` file for details of variables to set

Additionally, a Postman collection/env variables are provided under the `postman/` folder

### With Docker

```sh
docker-compose up --build
```

### Without Docker

```sh
npm run start:dev
```

NOTE: This project requires DB connectivity in order to start up, so you'll have to run an instance of Postgres locally and update the `DATABASE_HOST` .env variable with the correct value

## Run tests

```sh
npm run test
```

## Documentation

In addition to Swagger, documentation is autogenerated using [Compodoc](https://docs.nestjs.com/recipes/documentation)

```sh
npm run generate:docs
```

Compodoc documentation will be available at `localhost:8080`

Swagger documentation will be available at `localhost:3000/swagger` (or whatever port you're running the server on)

## Author

👤 **Nicholas McHenry**

- Github: [@nmchenry01](https://github.com/nmchenry01)

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
