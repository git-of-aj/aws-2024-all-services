[bucket policy vs IAM vs ACL](https://aws.amazon.com/blogs/security/iam-policies-and-bucket-policies-and-acls-oh-my-controlling-access-to-s3-resources/)
Q> S3 Full Access to IAM user + bucket Policy Only Allow to list and Get Object ? Can he upload objects ?
- Yes as no explicit deny, so he can inherit IAM permissions
- `DENY` - That He can't do 
