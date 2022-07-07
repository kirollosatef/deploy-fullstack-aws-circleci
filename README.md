# Hosting a Full-Stack Application

- Applications that are built on top of a full stack called Udagram [Link](http://deploy-rds-s3-eb-1234.s3-website-us-east-1.amazonaws.com/)

- documentation: [here](doc/README.md)

## about the Hosting (AWS)

This Udagram application was provided by Udacity.

### AWS services

- S3 (deploy Udagram application frontend)
- RDS (Database)
- Elastic Beanstalk (deploy Udagram application frontend)

### CircleCI

- [![CircleCI](https://circleci.com/gh/kirollosatef/deploy-fullstack-aws-circleci/tree/master.svg?style=svg)](https://circleci.com/gh/kirollosatef/deploy-fullstack-aws-circleci/tree/master)

## Requirements

### .env file

      AWS_ACCESS_KEY_ID=...
      AWS_DEFAULT_REGION=...
      AWS_SECRET_ACCESS_KEY=...
      URL=...
      POSTGRES_DB=...
      POSTGRES_HOST=...
      POSTGRES_PASSWORD=...
      POSTGRES_USERNAME=...
      PORT=...
      JWT_SECRET=...

### install dependencies

      npm run frontend:install
      npm run api:install

### build

      npm run frontend:build
      npm run api:build

### start

      npm run frontend:start
      npm run api:start
