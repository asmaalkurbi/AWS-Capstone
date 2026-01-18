# AWS-Project-Simple
AWS cloud technical essentials simple project

Description of the diagram:
The architecture runs in one AWS region and one VPC accross 2 different AZs to ensure availability. An internet gatewat allows public internet access to the VPC. An ALB manages traffic to EC2 instances, and these instances are part of an auto scaling group. A MySQL database is in a private subnet with not access from the internet. Network ACLs are attached to all subents and security groups secure the resources.
