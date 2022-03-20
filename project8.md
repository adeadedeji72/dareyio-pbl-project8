# **LOAD BALANCER SOLUTION WITH APACHE** ##

### **Task** ##
Deploy and configure an Apache Load Balancer for Tooling Website solution on a separate Ubuntu EC2 intance. Make sure that users can be served by Web servers through the Load Balancer.

We will implement this solution with 2 Web Servers, the approach will be the same for 3 and more Web Servers.

![image](Tooling-Website-Infras-wLB.png)

In our set up in Project-7 we had 3 Web Servers and each of them had its own public IP address and public DNS name. A client has to access them by using different URLs, which is not a nice user experience to remember addresses/names of even 3 server, let alone millions of Google servers.

In order to hide all this complexity and to have a single point of access with a single public IP address/name, a Load Balancer can be used. A Load Balancer (LB) distributes clients’ requests among underlying Web Servers and makes sure that the load is distributed in an optimal way.

From Project 7, 

Make sure that you have following servers installed and configured within Project-7:

Two RHEL8 Web Servers
One MySQL DB Server (based on Ubuntu 20.04)
One RHEL8 NFS server

![image](prerequisites-project8.png)

