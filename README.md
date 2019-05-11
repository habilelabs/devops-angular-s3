# Angular Website Deployment to S3
 Angular Website Deployment to S3 using CloudFormation

# Overview
This repo is a demonstration of Continuous Delivery of a angular website to S3 via CodeBuild and CodePipeline. To launch, you'll need to specify a unique S3 bucket name for the website bucket that will be created.

# Launch Stack

[![Launch CFN stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#cstack=sn%7Edevops-essentials-static%7Cturl%7Ehttps://s3.amazonaws.com/www.devopsessentialsaws.com/samples/static/pipeline.yml)


# Configure Solution

1. Once the CloudFormation stack is successful, select the checkbox next to the stack and click the **Outputs** tab. 
2. From **Outputs**, click on the **PipelineUrl** output. 
3. Once the pipeline is complete, go to your CloudFormation Outputs and click on the **SiteUrl** Output
