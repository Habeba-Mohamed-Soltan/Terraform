terraform {
  backend "s3" {
    encrypt = true 
    bucket = "testing-bucket-s3-st"
    dynamodb_table = "terraform-state-lock-dynamo"
    key    = "terraform.tfstate"
    region = "us-east-2"
  }
}
