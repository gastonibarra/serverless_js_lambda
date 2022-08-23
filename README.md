# serverless_js_lambda

## Description

This is a fuction writed in Javascript (Node.Js 12), with a 'GET' method. To run It, I configured Serverless.yml to deploy with Cloudformation on AWS.

## Configuration

```bash

$ sls deploy

Deploying lambda-function to stage dev (sa-east-1)

✔ Service deployed to stack lambda-function-dev (154s)

endpoint: GET - https://lpupp3z4z2.execute-api.sa-east-1.amazonaws.com/dev/hello
functions:
  hello: lambda-function-dev-hello (415 B)

Monitor all your API routes with Serverless Console: run "serverless --console"

```

### Example Test

endpoint: GET - https://lpupp3z4z2.execute-api.sa-east-1.amazonaws.com/dev/hello
