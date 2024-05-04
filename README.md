**Title:** Deploy a Static Website on AWS with Ansible

**Architecture Diagram:** 

![Alt text](/Ansible Reference Architecture.jpg)

**Website Screenshot:** 

![Alt text](/Website Screenshot.png)

**Prerequisites:**
1. Install Git
2. Install Visual Studio Code
3. Register for a GitHub account

**Deployment Steps:**
1. Create a Key Pair in the AWS Console.
2. Create a VPC with public and private subnets in 2 AZs.
3. NAT Gateway, Bastion Host, and Application Load Balancer use public subnets.
4. Create security groups.
5. Create key pairs on your computer.
6. Import public key pair into GitHub.
7. Add the public key into GitHub.
8. We will use the bastion host to connect the Ansible server in the private subnet.
9. The Ansible server is the EC2 instance we will install Ansible on.
10. The web servers are the EC2 instances that will host the website.
11. Add the private key into the Ansible server.
12. Test the connection between Ansible and web servers.
13. Create a GitHub repository on the Ansible server.
14. Clone the GitHub repository to your computer.
15. Install Ansible into the Ansible server.
16. Create the Ansible inventory file in your local repository and push it into GitHub.
17. Use Ansible to ping the web servers to test connection.
18. Create the Ansible config file in your local repository and push it to GitHub.
19. Create the Ansible playbook in your local repository and push it to GitHub.
20. Use an Application Load Balancer to distribute web traffic to EC2 instances in 2 AZs.
21. Use Route 53 to register domain and create a record set with wildcard.
22. Use AWS Certificate Manager to secure web communication on the website.
