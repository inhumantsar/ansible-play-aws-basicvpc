# aws-basicvpc

Creates a new VPC, public subnets, and an internet gateway. Optionally creates private subnets and a NAT gateway.

By default, "dev" creates a VPC at 10.0.0.0/16 and "prod" creates a similar one at 10.10.0.0/16.

## Usage

`ansible-playbook playbook.yml -i env/dev/hosts`
