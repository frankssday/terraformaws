# terraformaws

## Instructions
This exercise demonstrates
- The use of Terraform to provision an AWS S3 bucket
- The use of a programming language (Python) to interact with/transfer files to S3

## Prerequisites
- Python3 (3.6 or above)
- Terraform  (can be downloaded from [https://www.terraform.io/downloads.html](https://www.terraform.io/downloads.html))
- Python package Boto3 [https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html)
- AWS credentials properly configured. On Linux or Mac, this means
``` 
$ cat ~/.aws/credentials
[default]
aws_access_key_id = [your access key id]
aws_secret_access_key = [your secret access key]
```

## Run the example
```
$ git clone https://github.com/frankssday/terraformaws.git
$ cd terraformaws/
$ pip3 install -r requirements
$ ls
data.json  README.md  requirements  s3.tf  upload2s3.py
```

Assume that 'terraform' is already on the PATH
```
$ terraform init   (this is for first time use)
$ terraform apply
$ python3 upload2s3.py
```

