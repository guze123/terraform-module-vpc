# terraform-module-vpc

## Usage:

```hcl
module "ec2" {
  source  = "guze123/vpc/module"
  version = "0.0.1"
  region = "us-east-2"
  vpc_cidr = "10.0.0.0/16"
  public_cidr1 = "10.0.1.0/24"
  public_cidr2 = "10.0.2.0/24"
  public_cidr3 = "10.0.3.0/24"
  private_cidr1 = "10.0.101.0/24"
  private_cidr2 = "10.0.102.0/24"
  private_cidr3 = "10.0.103.0/24"
  key_name = "ohio-key"
  instance_type = "t2.micro"
}
```
