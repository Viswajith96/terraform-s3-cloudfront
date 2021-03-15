## How to run.

This script will create an S3 bucket for static hosting and which will get mapped to cloudfront for seamless content delivery.

update the access key and secret key before running script.

## Command to install

terraform init && terraform apply

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| bucket | Name of the s3 bucket to be created. | `string` | n/a | yes |
| region | Region where s3 bucket to be created. | `string` | `"us-east-1"` | no |


