# CloudFormation

### Declare what you need and run the template. 
### Automation needs less time.
### Updating Infrastructure is easy with CloudFormation.


## Parameters:
### • The dynamic input for your template.
### • Some inputs can’t be determined ahead of time.
### • If you want to reuse your templates.
### •	Parameters must be declared and referenced from within the same template. You can reference parameters from the Resources and Outputs sections of the template.
### •	You can have a maximum of 200 parameters in an AWS CloudFormation template.


## Resources:
### •	Resources are core of your CloudFormation template.
### •	You can include resources what you want in the stack. i.e., amazon EC2,S3….
### •	Depends_on is used one resource is depend on another resource.
### •	For example: EIP gets created only after internet gateway in a VPC created.
### •	The resource type identifies the type of resource that you are declaring. For example, AWS::EC2::Instance declares an EC2 instance.
### •	Resource properties are additional options that you can specify for a resource.



