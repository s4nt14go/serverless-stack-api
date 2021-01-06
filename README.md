Backend [Serverless Stack](https://serverless-stack.com) tutorial done, this repo corresponds to the Basics part. 

The backend consists of:
* Infrastructure: deploys S3, DynamoDB & Cognito, it's a [AWS CDK](https://aws.amazon.com/cdk) project with [SST](https://github.com/serverless-stack/serverless-stack) for deployment.
* APIs: deploys API Gateway and Lambdas, it uses [Serverless Framework](https://github.com/serverless/serverless) for deployment.

This Basics part bundles both components into this single repo. Also the Serverless Framework project bundles the notes and billing APIs in one serverless.yml file.

If you're interested in the extended version, which splits both components into separate repos and the APIs in different serverless.yml files check these other two repos: [Infrastructure](https://github.com/s4nt14go/serverless-stack-ext-resources) and [API](https://github.com/s4nt14go/serverless-stack-ext-api).   
