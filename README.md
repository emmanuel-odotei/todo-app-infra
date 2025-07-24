# Taskly ToDo App Infrastructure Setup
CloudFormation templates to provision taskly todo-ap infrastructure

## Instructions
- Create the following resources before creating these stacks in AWS Cloudformation:
1. AWS ECR private repo for your application
2. Infrastructure S3 bucket for the github actions in this repo to store the templates on S3
3. Parameters to store the app image uri and the base uri of the infrustructure S3 bucket created in step 2. In parameter store or replace the parameter store references in the main.yaml "Parameters" session on the file.
