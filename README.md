# Hosting a Full-Stack Application

I'm using the Udagaram Starter provided in Udacity. This is Application, where you can register an account and upload pictures and give comments to them.
## How to get started
First, make sure that the following dependencies are installed.
```

- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### *Installation*
First:
- clone this repo and navigate to the root directory
- install frontend dependencies 
`npm run frontend: install`
- install backend dependencies
`npm run api: install`

### *Build*
- build the frontend
`npm run frontend:build`
- build the backend
`npm run api:build`

## Starting app
- open two seperate terminals
- on the first: navigate to *udagram/udagram-api* and run
`npm start`
- on the second: navigate to *udagram/udagram-frontend* and run `npm start`as well

## Deployment
- run `npm run frontend:deploy` in root directory to deploy the frontend
- run `npm run api:deploy` in root directory to deploy the backend

>> By pushing new commits to your repository, the pipeline starts the deploy process by itself.
## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
