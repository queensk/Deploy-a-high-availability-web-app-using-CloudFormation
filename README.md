# Project Title - Deploy a high-availability web app using CloudFormation

A highly available application is a system or service that is designed to be operational and accessible to users with minimal downtime. The goal of high availability is to minimize or eliminate disruptions to the availability of the application, such as outages, slow performance, or data loss.

To achieve high availability, a number of techniques can be used, such as:

1. Redundancy: By having multiple copies of the application running on separate servers, if one server fails, the others can take over and keep the application running.
2. Load balancing: By distributing incoming requests across multiple servers, the application can handle high traffic and prevent a single server from becoming a bottleneck.
3. Failover: By having a secondary server or system that can take over in the event of a failure, the application can continue to operate even if there is an issue with the primary server or system.
4. Monitoring and alerting: By monitoring the application's performance and infrastructure, and alerting when issues arise, problems can be identified and addressed quickly, minimizing downtime.

## Resources

1. Virtual Private Cloud (VPC) - to create a virtual network for the web application
2. Internet Gateway - to allow traffic to flow in and out of the VPC
3. Public and Private Subnets - to create a public subnet for the web servers and a private subnet for the database
4. Elastic Load Balancer (ELB) - to distribute incoming traffic to multiple web servers
5. Auto Scaling Group - to automatically scale the number of web servers based on traffic
6. Security Group - to control access to the web servers
7. RDS instance - to create a database for the web application
