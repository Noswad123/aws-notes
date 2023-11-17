- aka VPC
- Logically isolated virtual network
- you get a default VPC in each [[AWS Region]]
- resembles a traditional network
# Components
Subnet
- separate areas within VPC that groups resources together
- can be public or private
- network access control list (ACL)
	- virtual firewall that controls inbound and outbound traffic at the subnet level
	- performs stateless packet filtering
		- does not remember packets
	- stateless and allows all inbound and outbound traffic by default
 
Internet gateway
- allows public traffic from the internet to access your VPC

Virtual Private gateway
- allows protected internet traffic to enter into the VPC
- you can establish a VPN connection between your VPC and private network

AWS Direct Connect
- Establish a dedicated private connection between your data center and a VPC

# Related

# Resources
[VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
[**network access control list (ACL)**](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html).