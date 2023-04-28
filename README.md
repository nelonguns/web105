# web105
web105 2020

provider "aws" {
  region = "us-east-1"
  access_key = "AKIAVTPPSFCJFKLLMK5N"
  secret_key = "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"
}

  resource "aws_instance" "my-Tutor-Tabot" {
  ami           = "ami-0c6c29c5125214c77"
  instance_type = "t2.micro"

}


# resource "<provider>_<resource_type>" "name" {
#     config options.....connection 
#       key = "value"
#       key2 = "another value"
# }
