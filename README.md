# terraform-aws-asg
For Aws provider a module to create Auto Scaling Group and Elastic Load Balancer.
module "asg" {
  source  = "tuyalou/asg/aws"
  version = "1.0.0"
  # insert the 5 required variables here
}

# Variables :
  region = "us-east-1" 
  image_owner = "137112412989" 
  desired_capacity = 1 
  max_size = 1 
  min_size = 1 
