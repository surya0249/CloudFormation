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




## Mappings: 
### •	Mappings are fixed variables with your cloudformation template.
### •	They are very handy to differentiate between different Env, regions,
###   AMI types.
### •	All these are hardcoded in the template.
### •	Mappings are great when you know in advance all the values that can be taken and that they are deduced from variables such as
###   Region
###   Availability Zone
###   Aws account
###   Environment[dev,prod]
###   !Findmap [ mapname, toplevel key, second level key]



## Outputs:
### •	The output section declares optional output values that we can import into other stacks.
### •	You can also view output in AWS console or AWS cli.
### •	You need to export the output value before being able to use it in another stack.



## Conditions:
### •	Conditions are used to control the creation of resources or output based on a condition.
### •	Condition can be whatever you want them to be, but common are
###   Environment
###   AWS region
###   Any parameter value
### •	Each condition can reference another condition parameter value or mapping.



## Drift:
### Drift is the difference between the expected configuration values of stack resources defined in CloudFormation templates and the actual configuration values of these resources in the corresponding CloudFormation stacks.



### 1.	Login to your AWS account and head over to the AWS CloudFormation console.
### 2.	we will launch a new stack which will launch Security group. Click on the "Create Stack" button.
### 3.	Upload template file.


![image](https://user-images.githubusercontent.com/48580661/120105930-8f56d180-c178-11eb-8530-71c806bdb89f.png)


### 4. Click "Next" and enter the stack name and specify parameter values.
![image](https://user-images.githubusercontent.com/48580661/120106136-861a3480-c179-11eb-8869-2d00049ccb85.png)











