# Hashicat instance Terraform Module #

## Usage

Check valid versions on:
* Github Releases: <https://github.com/jeromebaude/terraform-aws-hashicat-module>

        module "hashicat-aws-instance" {  
            source              = "app.terraform.io/jerome-playground-2019/hashicat-module/aws"
            version             = 1.1.2
            prefix              = "${var.prefix}"
            profile             = "${var.profile}"
            height              = "${var.height}"
            width               = "${var.width}"
            placeholder         = "${var.placeholder}"
       }


## Input values

prefix: Your name

height: height of the image

width: width of the image

placeholder: image

## Output values

catapp_url: URL of the application
