# AWS-Lambda-CI-CD-Template
A template for creating CI/CD environments for AWS Lambda functions

## Challenge:

Implementing version control for AWS Lambda functions is not a trivial task. This is because AWS offers multiple different methods for deploying and invoking different versions of AWS Lambda functions. Each method has its strengths and weaknesses.

One approach to implement Git-style version control for Lambda functions is to use Chalice to deploy AWS Lambda functions for multiple stages. The concept of “stage” in the context of AWS Lambda is a fuzzy one, but essentially by defining multiple stages in our Chalice configuration, we are able to create multiple AWS Lambda functions with their own independent API Gateways.
