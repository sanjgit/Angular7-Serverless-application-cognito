Angular7-AWS(Cognito-Lamda-ApiGateway-S3-cloudfront-DynamoDB)
===================================================


## What does this app do?
![QuickStart Angular7 Cognito App](Serverless_Web_App_LP_assets.png?raw=true)

## Tech Stack
### Required Tools
* [aws cli](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
* [eb cli](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html)
* [npm](https://www.npmjs.com/)
* [angular-cli](https://github.com/angular/angular-cli)

### Frameworks
* [AWS JavaScript SDK](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/browser-intro.html)
* [Angular 7](https://angular.io/docs/ts/latest/quickstart.html)
    * [TypeScript](https://www.typescriptlang.org/docs/tutorial.html)
* [Bootstrap](http://getbootstrap.com/)

## AWS Setup
##### Install the required tools (the installation script only runs on Linux and Mac)
* Create an AWS account
* Install [npm](https://www.npmjs.com/)
* [Install or update your aws cli](http://docs.aws.amazon.com/cli/latest/userguide/installing.html) 
* [Install or update your eb cli](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html) 
* [Install angular-cli](https://github.com/angular/angular-cli)


## Getting the code and running it locally
_This uses the pre-configured AWS resources hosted by AWS_

```
# Clone it from github
git clone --depth 1 git@github.com/sanjgit/Angular7-Serverless-application-cognito.git
```
```
# Install the NPM packages
cd Angular7-Serverless-application-cognito
npm install
```
```
# Run the app in dev mode
ng serve
```

## Creating AWS Resources
This sample application can be deployed to either Elastic Beanstalk or S3. S3 will host this application as a static site
while Elastic Beanstalk gives you the capability of adding backend operations to the application. 

* [build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito](https://aws.amazon.com/getting-started/projects/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)


