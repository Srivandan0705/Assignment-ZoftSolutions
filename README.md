# Assignment-ZoftSolutions
This Repository contains Cloud formation templates of VPC deployment with two public and private subnets across availability zones and also Lambda integration with API Gateway

Cloudformation Template files:

1) **Assmnt-VPC.yaml** - This template deploys a VPC, with a pair of public, private subnets spread across two Availability Zones.
   This template also contains Parameters for input the value while creating stack and also Outputs to export the values.

2) **Assmnt-LambdaAPI.yaml** - This template deploys a Private REST API Gateway and Lambda FUNCTION and integrates the function with Gateway

3)** Buildspec.yaml** - This field contains build steps for CodeBuild
