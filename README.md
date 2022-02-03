# AWS-China-Technical-Best-Practice

### IAM users and policies

No root user
No concept of “root” or “account” user or credentials. All users are IAM users, including the user who created the account.
<img width="1348" alt="image" src="https://user-images.githubusercontent.com/81153899/152358430-03d86c38-ba9d-4d44-9d28-0bb849092395.png">

Amazon Resource Name (ARN) syntax
ARN includes the aws-cn partition for resources in the region. For example: 
arn:aws-cn:iam::123456789012:user/ericademo
The detail is https://docs.amazonaws.cn/en_us/aws/latest/userguide/ARNs.html

### Set up CLI and SDK
AWS CLI and SDK are same with global regions
https://aws.amazon.com/cli
https://aws.amazon.com/tools/

China Region name
Beijing: cn-north-1 
Ningxia: cn-northwest-1


### Service Endpoint access

servicename.cn-north-1.amazonaws.com.cn
servicename.cn-northwest-1.amazonaws.com.cn 

Please check the details https://docs.amazonaws.cn/en_us/aws/latest/userguide/endpoints-arns.html. 

