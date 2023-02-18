# Week 0 — Billing and Architecture

## Required Homework/Tasks

### Install AWS CLI

I am providing the command result after the installation. 


```
jason@Jasons-MacBook-Pro aws-bootcamp-cruddur-2023 % aws --version
aws-cli/2.8.13 Python/3.9.11 Darwin/21.6.0 exe/x86_64 prompt/off
jason@Jasons-MacBook-Pro aws-bootcamp-cruddur-2023 %


jason@Jasons-MacBook-Pro aws-bootcamp-cruddur-2023 % aws configure list
      Name                    Value             Type    Location
      ----                    -----             ----    --------
   profile                <not set>             None    None
access_key     ****************ATGL shared-credentials-file
secret_key     ****************IcqM shared-credentials-file
    region                us-east-1      config-file    ~/.aws/config
jason@Jasons-MacBook-Pro aws-bootcamp-cruddur-2023 % aws sts get-caller-identity
{
    "UserId": "AIDAWF2ABWU5EGUO3MDJG",
    "Account": "424799221050",
    "Arn": "arn:aws:iam::424799221050:user/Jia.Yu@kyndryl.com"
}
jason@Jasons-MacBook-Pro aws-bootcamp-cruddur-2023 %


```


## Homework Challenges



