# VPC (Virtual Private Cloud) – Learning Notes

## What I Learned
* A VPC is a logically isolated network in AWS
* Subnets divide VPC CIDR blocks (public vs private)
* Internet Gateway enables public access
* Security Groups = instance-level firewall (stateful)
* NACLs = subnet-level firewall (stateless)

## Architecture Understanding
* Public subnets: route to IGW
* Private subnets: route to NAT for outbound internet

## Next Steps
* Build a custom VPC with public and private subnets
* Launch EC2 instances in both to test connectivity
