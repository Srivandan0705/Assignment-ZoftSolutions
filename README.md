# Assignment-ZoftSolutions
This Repository contains Cloud formation templates of VPC deployment with two public and private subnets across availability zones and also Lambda integration with API Gateway

**Cloudformation Template files:**


1) **Assmnt-VPC.yaml** - This template deploys a VPC, with a pair of public, private subnets spread across two Availability Zones.
   This template also contains Parameters to pass input values while creating the stack and also Output to export the values.

2) **Assmnt-LambdaAPI.yaml** - This template deploys a Private REST API Gateway and Lambda FUNCTION and integrates the function with Gateway. This template imports a value from Assmnt-VPC template.

3) **Buildspec.yaml** - This field contains build steps for CodeBuild
