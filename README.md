# AWS-China-Technical-Best-Practice

### IAM users and policies

No concept of “root” or “account” user or credentials. All users are IAM users, including the user who created the account.

Amazon Resource Name (ARN) syntax

ARN includes the aws-cn partition for resources in the region. For example:  

arn:aws-cn:iam::123456789012:user/ericademo 

The detail is https://docs.amazonaws.cn/en_us/aws/latest/userguide/ARNs.html

### Set up CLI and SDK
AWS CLI and SDK are same with global regions  
https://aws.amazon.com/cli  
https://aws.amazon.com/tools/  

China Region name \
Beijing: cn-north-1  \
Ningxia: cn-northwest-1

### Service Endpoint access

servicename.cn-north-1.amazonaws.com.cn  
servicename.cn-northwest-1.amazonaws.com.cn 

Please check the details https://docs.amazonaws.cn/en_us/aws/latest/userguide/endpoints-arns.html. 

