# CloudFormation
Resource creation in AWS using CloudFormation(CFT)

It's a tool provided by AWS that allows you to define your infrastructure as code, meaning you can write a script (using a language called JSON or YAML) that describes the resources you want to create, their configurations, and how they're connected.

In this project i have created 2 instances and one S3 bucket.
The steps involved are as follows:

1. Created a cloudformation template as per the requirement.
2. Upload the CFT template from your machine.
3. Create cloudformation stack.
4. Monitor and check the resources created.
5. If you no longer need the resources created by the CloudFormation stack, you can delete the stack from the CloudFormation console. This will automatically delete all 
   associated resources, including the EC2 instance and S3 bucket, to avoid incurring unnecessary costs
