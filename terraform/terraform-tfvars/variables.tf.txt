variable "region" {
  default = "ap-south-1"
}

variable "instance_type" {
  default = "t2.micro"
}

variable "ami_id" {
  default = ""
}

variable "key_name" {
  default = "win_ec2"
}

variable "subnet_id" {
   default = "subnet-0d656c4b7c43554af"
}
