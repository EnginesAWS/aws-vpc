# aws-vpc
The VPC blueprint for most deployments will be handwritten There is a pile of stuff to add here in terms of vpc setup/configuration and of bindings added to vpc

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc

resource "aws_vpc" "something" {
  cidr_block       = "10.0.0.0/16"
  instance_tenancy = "default"

  tags = {
    Name = "something"
  }
}


}
