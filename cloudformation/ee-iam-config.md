## Policy Statements

```
[
        {
            "Effect": "Allow",
            "Action": [
                "lambda:*",
                "dms:*"
            ],
            "Resource": "*"
        }
    ]
```

## IAM Managed Policy ARNs

```
arn:aws:iam::aws:policy/IAMFullAccess
arn:aws:iam::aws:policy/AmazonS3FullAccess
arn:aws:iam::aws:policy/AWSCloudFormationFullAccess
arn:aws:iam::aws:policy/AWSGlueConsoleFullAccess
arn:aws:iam::aws:policy/AWSLakeFormationDataAdmin
arn:aws:iam::aws:policy/AmazonRDSFullAccess
arn:aws:iam::aws:policy/AWSLambdaFullAccess
arn:aws:iam::aws:policy/job-function/NetworkAdministrator
```

## IAM Trusted Services

```
ec2.amazonaws.com
glue.amazonaws.com
dms.amazonaws.com
rds.amazonaws.com
lambda.amazonaws.com
```


## IAM Service Linked Roles

```
None
```