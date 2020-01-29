# Hashicat instance Terraform Module #

## Usage

Check valid versions on:
* Github Releases: <https://github.com/jeromebaude/terraform-gcp-hashicat-module>

        module "hashicat-aws-instance" {  
            source              = "app.terraform.io/jerome-playground/hashicat-module/gcp"
            version             = 1.0.1
            prefix              = var.prefix
            height              = var.height
            width               = var.width
            placeholder         = var.placeholder
       }


## Input values

prefix: Your name

height: height of the image

width: width of the image

placeholder: image

## Output values

catapp_url: URL of the application
