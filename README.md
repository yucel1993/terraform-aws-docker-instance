Usage:

```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "yucel1993/docker-instance/aws"
    key_name = "clarusway"
}
```
