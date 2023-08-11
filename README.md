# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
1. In AWS, provision a s3 bucket for hosting the uploaded files.
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv).
1. After installation is done start the api in dev mode with `npm run dev` and `npm run start`.

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End-to-End Tests:

The e2e tests are using Protractor and Jasmine.

### Front-End Link:

1. http://udagram-s3-buckets.s3-website-ap-southeast-2.amazonaws.com

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
