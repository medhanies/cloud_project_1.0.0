# Create three tier VPC Architecture

    - build vpc using terraform modules
    - two availability zones in us-east-1
    - each az will have one public subnet with a nat gateway and 2 private subnets for ec2 instances and databases respectively

# Create a bastionHost

    - Create AWS EC2 Bastion Host used to connect to EKS Node Group EC2 instances

# Create EKS Cluster and node groups

    - tie everything together from above
    - create eks cluster
    - create one public and one private node group and provision the ec2 instances that will run in them
