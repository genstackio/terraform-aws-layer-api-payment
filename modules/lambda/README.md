# AWS API Payment Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
payment on AWS.

## Usage

```hcl
module "lambda-api-payment" {
  source = "genstackio/layer-api-payment/aws//modules/lambda"

  name   = "my-lambda-api-payment"
}
```
