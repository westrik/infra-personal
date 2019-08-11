# infra-personal

- sets up a VPC, subnet, and security group
- provisions a t3a.micro EC2 node with a generated key pair

## Usage

Install `terraform` and set `$AWS_ACCESS_KEY_ID`  and `$AWS_SECRET_ACCESS_KEY`, then run:

```sh
terraform init
terraform plan # preview changes (optional)
terraform apply
```
