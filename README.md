# infra-personal

- sets up a VPC, subnet, and security group
- provisions a t3a.micro EC2 node with a custom AMI (built with Packer)

## Usage

Install `terraform`+`packer`, set `$AWS_ACCESS_KEY_ID`  and `$AWS_SECRET_ACCESS_KEY`, and then run:

```sh
terraform init
packer build westrikworld.json
terraform plan # preview changes (optional)
terraform apply
```
