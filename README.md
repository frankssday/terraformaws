# terraformaws

## Prerequites
- Python3 (3.6 or above)
- Terraform  (can be downloaded from [https://www.terraform.io/downloads.html](https://www.terraform.io/downloads.html)
- Python package Boto3


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
$ terraform init
$ terraform apply
$ python3 upload2s3.py
```

