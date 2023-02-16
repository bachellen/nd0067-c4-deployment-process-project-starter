# Udagram

### **An application provided by udacity to be hosted into AWS using Circleci pipeline.to complete FullStack JavaScript Developer NanoDegree**


## Link to hosted project 

    S3 Endpoint - Frontend: http://udagram-muhailah.s3-website-us-east-1.amazonaws.com/

    Elastic Beanstalk URL - Backend: http://udagram-api2-dev2.us-east-1.elasticbeanstalk.com

## Screenshots 

#### AWS Elastic Beanstalk
  
<img width="1440" alt="aws_elasticbeanstalk" src="https://user-images.githubusercontent.com/37004139/219228966-cbb02e74-a1c2-43c2-b77f-8d48cfd7558f.png">


#### AWS RDS Database
  
<img width="1440" alt="aws-rds-database" src="https://user-images.githubusercontent.com/37004139/219229038-4c2dbbe8-c9de-407d-8a79-0ff0c0477c4a.png">


#### AWS S3 bucket (frontend hosting)
  
<img width="1440" alt="aws-s3-bucket(frontend-hosting)" src="https://user-images.githubusercontent.com/37004139/219229105-b11e3e90-02da-4bde-af28-6485ec4ac8f6.png">


#### CircleCI overveiw  

<img width="1440" alt="circleci" src="https://user-images.githubusercontent.com/37004139/219229210-64e8182f-6105-4667-a558-0f1cb35ccd6f.png">


#### CircleCI build 

<img width="1440" alt="circleci-build" src="https://user-images.githubusercontent.com/37004139/219229350-cf665386-73f0-4c55-867c-d4eac8ec0633.png">


#### CircleCI deploy 

<img width="1440" alt="circleci-deploy" src="https://user-images.githubusercontent.com/37004139/219229449-e776f0b9-ee22-4b2d-b14d-d90993b51dfe.png">


#### CircleCI environment variables

<img width="1440" alt="circleci-enviroment-vars" src="https://user-images.githubusercontent.com/37004139/219229577-0b122173-e909-4a0c-9ca0-4d5d2c590ec1.png">




### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

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
