# Angular Website Deployment to S3
 Angular Website Deployment to S3 using CloudFormation

# Overview
This repo is a demonstration of Continuous Delivery of a angular website to S3 via CodeBuild and CodePipeline. To launch, you'll need to specify a unique S3 bucket name for the website bucket that will be created. At the conclusion, you will be able to provision all of the AWS resources by clicking a "Launch Stack" button and going through the AWS CloudFormation steps to launch a solution stack.
In this example, all the source files are hosted in GitHub and can be made available to developers. All of the steps in the process are orchestrated via CodePipeline and the build and deployment actions are performed by CodeBuild. The provisioning of all of the AWS resources is defined in a CloudFormation template.
By automating the actions and stages into a deployment pipeline, you can release changes to users in production whenever you choose to do so without needing to repeatedly manually upload files to S3. Instead, you just commit the changes to the GitHub repository and the pipeline orchestrates the rest. While this is a simple example, you can follow the same model and tools for much larger and sophisticated applications.

# Launch Stack

[![Launch CFN stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#cstack=sn%7Edevops-essentials-static%7Cturl%7Ehttps://s3.amazonaws.com/www.devopsessentialsaws.com/samples/static/pipeline.yml)


# Configure Solution

1. Once the CloudFormation stack is successful, select the checkbox next to the stack and click the **Outputs** tab. 
2. From **Outputs**, click on the **PipelineUrl** output. 
3. Once the pipeline is complete, go to your CloudFormation Outputs and click on the **SiteUrl** Output
