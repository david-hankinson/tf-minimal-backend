# A Minimal Terraform Deploy Repository

Simple base code repository with an AWS S3 Backend and Dynamo DB Table for tf lock based on [Terraform Up and Running: 3rd Edition](http://www.terraformupandrunning.com/)

Using an S3 backend has the following advantages:
- [S3](https://aws.amazon.com/s3/) is a managed service so no need for effort in setting up infra
- [DynamoDB](https://aws.amazon.com/dynamodb/) provides a simple service for managing Terraform lock
- Secrets are not stored in plaintext!


Prerequisites:

- AWS Account
- Terraform installed locally
- Local system configured to interact with AWS account

Useage: 

```
terraform init

terraform plan

terraform appl
```



