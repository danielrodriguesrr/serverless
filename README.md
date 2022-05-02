Project for AWS Lambda functions in Node, deployed using Serverless
==============================================================================

Use this project as a way to learn more AWS Lambda
function (or collection of functions) in Nodejs. It assumes that you are using
Nodejs 12.x.

## Prerequisites (on your computer or build server):

 * Node.js
   * npm
 * Serverless Framework
   * Serverless offline

## Getting started

Create a user in IAM AWS on your account on AWS and with your access key and secret key, run the follwing command:
    `serverless config credentials -o --provider aws --key=[accessKey] --secret=[secretKey]`

This repository doesn't have dependencies so there is no need to install dependencies on this project.

## Testing

Run `serverless offline` to run your application on your local machine.

## Deploy

Run `serveless deploy` to deploy your project to AWS Lambda.