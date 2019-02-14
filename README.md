# terraform-
provider="aws"{
region="us_east2"
}
resource "aws_instance" "web" {
  ami           = "${data.aws_ami.ubuntu.id}"
  instance_type = "t2.micro"

  tags = {
    Name = "HelloWorld"
  }
}
resource="aws_security_group"(public subnet1)
data="$(

