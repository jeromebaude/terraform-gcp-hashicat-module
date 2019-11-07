# Hashicat instance Terraform Module #

## Usage

Check valid versions on:
* Github Releases: <https://github.com/jeromebaude/terraform-hashicat-module>

        module "hashicat-aws-instance" {  
            source              = "app.terraform.io/jerome-playground-2019/hashicat-aws-instance"
            version             = 1.0
            prefix              = "${var.prefix}"
            profile             = "${var.profile}"
            ami                 = "${var.ami}"
            height              = "${var.height}"
            width               = "${var.width}"
            placeholder         = "${var.placeholder}"
       }


## Input values

## Output values

