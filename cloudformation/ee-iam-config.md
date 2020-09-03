## Policy Statements

```
[
        {
            "Effect": "Allow",
            "Action": [
                "lambda:*",
                "dms:*",
                "lakeformation:*",
                "cloudtrail:DescribeTrails",
                "cloudtrail:LookupEvents",
                "glue:GetDatabase",
                "glue:GetDatabases",
                "glue:CreateDatabase",
                "glue:UpdateDatabase",
                "glue:DeleteDatabase",
                "glue:GetConnections",
                "glue:SearchTables",
                "glue:GetTable",
                "glue:CreateTable",
                "glue:UpdateTable",
                "glue:DeleteTable",
                "glue:GetTableVersions",
                "glue:GetPartitions",
                "glue:GetTables",
                "glue:GetWorkflow",
                "glue:ListWorkflows",
                "glue:BatchGetWorkflows",
                "glue:DeleteWorkflow",
                "glue:GetWorkflowRuns",
                "glue:StartWorkflowRun",
                "glue:GetWorkflow",
                "s3:ListBucket",
                "s3:GetBucketLocation",
                "s3:ListAllMyBuckets",
                "s3:GetBucketAcl",
                "iam:ListUsers",
                "iam:ListRoles",
                "iam:GetRole",
                "iam:GetRolePolicy"                
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
arn:aws:iam::aws:policy/AmazonRDSFullAccess
arn:aws:iam::aws:policy/AWSLambdaFullAccess
arn:aws:iam::aws:policy/AmazonAthenaFullAccess
arn:aws:iam::aws:policy/job-function/NetworkAdministrator
```

## IAM Trusted Services

```
ec2.amazonaws.com
glue.amazonaws.com
dms.amazonaws.com
rds.amazonaws.com
lambda.amazonaws.com
cloudformation.amazonaws.com
lakeformation.amazonaws.com
athena.amazonaws.com
```


## IAM Service Linked Roles

```
None
```