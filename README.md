# S3 Backend Module

This module will deploy an S3 remote backend for Terraform

## A sample configuration for sourcing a module from a GitHub repo is as follows:

```h
module "s3backend" {
   source ="github.com/aoshfan/terraform-aws-s3backend"
}
```

You can use a generic Git address to version-control GitHub modules by specifying a branch or tag name. Generic Git URLs are prefixed with the address git::

Link terraform registry: https://registry.terraform.io/modules/aoshfan/s3backend/aws/latest
