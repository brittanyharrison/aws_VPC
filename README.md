# AWS - Virtual Private Cloud (VPC)
Amazon VPC is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You can control your virtual network environment including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. You can use both IPv4 and IPv6 for most resources in your virtual private cloud, helping to ensure secure and easy access to resources and applications.

## Internet Gateway (IGW)
An Internet gateway can transfer communications between an enterprise network and the Internet. The gateway converts information, data or other communications from one protocol or format to another. A router may perform some of the functions of a gateway.

- They provide a target in your VPC route tables for internet-routable traffic
- perform network address translation (NAT) for instances that have been assigned public IPv4 addresses

## Subnet 
A subnet, or subnetwork, is a segmented piece of a larger network. One goal of a subnet is to split a large network into a grouping of smaller, interconnected networks to help minimize traffic.

- Groups of isolated resources can be placed in each segment of a VPC's IP address ranges
- Can be used to limit IP's used

## Route Table 
A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet or gateway is directed. 

## Network Access Control List (ACL) 
Network Access Control (NAC) is a computer networking solution that uses a set of protocols to define and implement a policy that describes how to secure access to network nodes by devices when they initially attempt to access the network.

- limiting user access
- blocks access from endpoint devices that do not comply with corporate security policies.

# Creating and Setting up VPC 

**Step 1: Create a VPC**
1. On the AWS Dashboard search for **VPC** and click on `Your VCP`.

2. Select `Create VPC`
![img](img/Create_VPC.png)

3. Create a **Name tag** , add an **IPv4 CIDRblock** and click `Create VPC`

![img](img/VPC_Settings.png)

**Step 2: Create Internet Gateway**
1.  Select `Internet Gateways` on the dashboard thenlect `Create Internet gateway` 


