## Cloud resume
- A cloud resume challenge to help people to get ready for a job in the cloud industry

## Tech and Services
- AWS
- HTML,CSS and Javascript
- Static website(Amazon S3 static website)
- HTTPS(for security),we will need Amazon CloudFront for that
- DNS(we can use Amazon Route 53)
- Database(Dynamo DB)
- API(AWS API gateway and Lambda)
- Python
- Git
- Infrastructure as Code
- CI/CD(for back-end we set up Github Actions)
- CI/CD(for front-end )

## Setup
- Create an AWS account at  https://aws.amazon.com/resources/create-account/
- Setup MFA for the root account  https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html
- Create an IAM user and assign permissions
- Setup vault  https://github.com/99designs/aws-vault and add user using these commands
  - aws-vault add my-user


## Deploy S3 
- In this step we are going to deploy S3 using AWS SAM(Serverless Application Model);an open-source framework for building serverless applications
- Set up the SAM CLI at https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html
- Add IAM permissions for SAM
  - CloudFormation
  - IAM
  - Lambda
  - API Gateway

