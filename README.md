# nestjs-serverless-starter

Starter kit using nestjs with serverless


## Description

This application uses the [Nest](https://github.com/nestjs/nest) web app framework for implementing the API and the [Serverless](https://serverless.com) CLI for managing deployments to AWS.

This is a Nest web app deployable as a lambda function.

## Before you start!
Do a find and replace to replace the string `<project-name>`, including the brackets, with your project name.

## Prequisites

Requires serverless installed on your mac

```bash
$ npm i -g serverless
```

## Installation

```bash
$ npm ci
```

## Running the app

```bash
# run locally
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

## Deploy (from local machine)

```bash
# deploy from your mac
$ npm run sls:deploy

# teardown / delete deployment
$ npm run sls:remove
```