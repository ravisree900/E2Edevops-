```
export AWS_ACCESS_KEY_ID = ####
export AWS_SECRET_ACCESS_KEY = ####
export AWS_SESSION_TOKEN = ####

unset AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_SESSION_TOKEN

aws sts get-caller-identity

aws sts assume-role --role-arn arn:aws:iam::1234567890/role/eks-cluster-role --role-session-name AWSCLI-Session

```
