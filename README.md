# AWS Serverless Lambda API Lab

A serverless REST API demonstration built on AWS Lambda, Amazon API Gateway, and Python.

## Architecture
1. Client sends an HTTP request to API Gateway.
2. API Gateway routes the request to AWS Lambda.
3. AWS Lambda executes lambda_handler, logs execution details to Amazon CloudWatch, and returns a JSON response back to the client.

---

## Live Endpoint Verification
```json
{
  "status": "success",
  "message": "Hello, Cloud Engineer! Your AWS Lambda function executed successfully.",
  "aws_request_id": "a0c13df3-7c9e-410b-a5b1-16a1660a9533"
}
```

---

## Tech Stack
* Cloud Provider: AWS (Lambda, API Gateway, CloudWatch)
* Language: Python 3.12
* Version Control: Git / GitHub
