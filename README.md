# Protected-VPC-with-Public-Workload

We will create an AWS Network Firewall in a VPC and configure it to allow web traffic to a webserver in a protected subnet. To accomplish this, we will complete the following steps:

1. Create a VPC, firewall subnet, protected web server subnet, internet gateway and web server. 
2. Create the firewall
3. Route traffic through the firewall
4. Set-up the firewall logging with Cloudwatch
5. Configure the firewall policy

At the end of this project, you will have created the diagram below.

![image](https://github.com/ericksonaspa/Protected-VPC-with-Public-Workload/assets/77118362/4666dade-2bd7-48d6-a239-7393a33329c1)

## Create a VPC

