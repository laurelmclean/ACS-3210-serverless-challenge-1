# Serverless Express API with DynamoDB

This project is a completed implementation of a Serverless REST API using Express.js and DynamoDB, based on this [tutorial](https://www.serverless.com/blog/serverless-express-rest-api/). It showcases how to leverage the benefits of Serverless while utilizing the familiar Express.js framework and ecosystem.

## Overview

Serverless deployments offer lightning-fast deployments, automatic scaling, and cost optimization with pay-per-execution pricing. However, transitioning to serverless can have a learning curve, requiring understanding of the underlying platform and its intricacies.

In this tutorial, I learned how to create a Serverless REST API using Express.js. By following the step-by-step walkthrough provided in the tutorial, I was able to achieve the following:

- Deploy a simple API endpoint
- Integrate a DynamoDB table for creating and retrieving User objects
- Implement path-specific routing for detailed metrics and monitoring
- Configure my local development environment for faster development iterations

## Getting Started

To run this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the project dependencies by running `npm install` in the project directory.
3. Configure your AWS credentials by following the instructions provided by the Serverless Framework.
4. Update the necessary configuration files with your AWS credentials and other required details.

Please refer to the tutorial for detailed instructions on each step.

## Prerequisites

Before running this project, make sure you have the following prerequisites installed:

- Node.js and npm (Node Package Manager)
- Serverless Framework
- AWS account and credentials

## Usage

To deploy the Serverless Express API, use the following command:

```
sls deploy
```

This command will deploy your API to your configured AWS account. Once the deployment is complete, you will receive the API endpoint URL.

## Local Development

For local development, you can use the following command to run the API locally:

```
sls offline start
```

This will start a local development server that mimics the behavior of the deployed API. You can then test your endpoints locally, speeding up the development process.
