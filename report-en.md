# AWS SERVICE IMPLEMENTATION REPORT
                 
Date: September 15, 2024
 
Company: Lecter Industries
 
Context: Lecter Industries has a head office and two branches. 
This project demonstrates the use of the initial services of Amazon Web Services to interconnect the network and run the applications of the entire company.

Responsible: Jonas Fernando Schuh

## Introduction
This report presents the process of implementing tools at Lecter Industries, carried out by Jonas Fernando Schuh.

The objective of the project was to list 3 AWS services, with the purpose of achieving immediate cost reduction.

## Project Description
The tool implementation project was divided into 3 stages, each with its specific objectives. The project steps will be described below:

Step 1: Network Configuration with AWS Virtual Private Cloud (VPC)
- Name of the tool: AWS Virtual Private Cloud (VPC)
- Focus of the tool: Creating a secure and scalable private network.
- Description of the use case: Setting up a VPC that interconnects the headquarters and the two branches, creating specific subnets for each unit. Using VPN or AWS Direct Connect to connect the local network of each branch to the VPC in the cloud, ensuring secure communication between all units.

Step 2: Identity and Access Management with AWS Identity and Access Management (IAM)
- Name of the tool: AWS Identity and Access Management (IAM)
- Focus of the tool: Access control and identity management.
- Description of the use case: Implement security policies and access control for users and applications, ensuring that only authorized people have access to specific resources according to their roles. Define roles and permissions for access to critical applications and data, centralizing identity management for all units of the company.

Step 3: Application Hosting with AWS Elastic Beanstalk
- Name of the tool: AWS Elastic Beanstalk
- Focus of the tool: Simplified application deployment and management.
- Description of the use case: Use Elastic Beanstalk to host and manage Lecter Industries' applications, ensuring high availability and automatic scalability.
- Integrate with other AWS tools, such as RDS for databases and S3 for storage, ensuring a robust environment for the company's systems to operate.

## Conclusion
The implementation of tools at Lecter Industries has the expected benefits of these tools, which will increase the company's efficiency and productivity.

It is recommended that the implemented tools continue to be used and that new technologies that can further improve the company's processes be sought.

### Summary Benefits of the Tools:
- AWS VPC: Ensures a secure and customized network, interconnecting headquarters and branches in an efficient and scalable manner.
- AWS IAM: Provides granular access control, ensuring that only authorized users can access specific resources, improving security.
- AWS Elastic Beanstalk: Simplifies application management, reducing the need for manual operations and allowing rapid adaptation to changes in demand.

### Financial Cost Reduction Comparison:
- Reduction in Local Infrastructure: Using AWS eliminates the need for physical servers and complex local network infrastructure, significantly reducing maintenance, electricity and physical space costs.
- On-Demand Scalability: AWS tools allow you to automatically scale resources as needed, avoiding spending on idle capacity.
- Lower Operating Costs: Automation and centralized management reduce the need for large IT teams for monitoring and maintenance, reducing personnel costs.

### Financial comparison between an on-premise server and AWS services.

The main costs involved in both options were considered. This analysis will include initial and recurring costs, such as hardware, maintenance, electricity, support, as well as costs associated with AWS services, such as instance usage, storage, and data traffic.

1. On-Premise Server Costs
Initial Costs:
- Hardware: Purchase of physical servers, switches, routers, firewalls, etc.
Estimate: Between $5,000 to $20,000 USD per server, depending on capacity and specifications.
- Infrastructure: Installation of racks, cabling, air conditioning systems, and backup power (UPS).
Estimate: Approximately $5,000 to $15,000 USD.
- Software Licensing: Licenses for operating systems, databases, and other management software.
Estimate: $1,000 to $5,000 USD per server, depending on the software used.

Annual Operating Costs:
- Hardware Maintenance: Replacement of components, repairs, and hardware upgrades.
Estimate: About 10-15% of initial hardware cost per year ($500 to $3,000 USD).
- Electricity: Electricity consumptionica of servers and cooling systems.
Estimate: Between $1,000 to $2,500 USD per server per year.
- Personnel Costs: IT staff for maintenance, monitoring, and management.
Estimate: $30,000 to $60,000 USD per year (for a minimum team).
- Support and Warranty: Additional support and warranty plans for the hardware.
Estimate: Around $1,000 to $3,000 USD per year.

Total Estimate for On-Premise Server (5 years):
Total Cost (5 years): Approximately $70,000 to $150,000 USD (considering all the factors mentioned).

2. Cost of AWS Services
Initial Costs:
- Infrastructure: There are no significant upfront costs as the infrastructure is managed by AWS.
- Annual Operating Costs:
EC2 (Elastic Compute Cloud) Instances: To run servers equivalent to an on-premise server.
Estimate: t3.medium instance (for light workloads): Approximately $500 to $1,000 USD/year. m5.large instance (for more intensive workloads): Approximately $1,800 to $3,600 USD/year.
- Storage (S3 and EBS): Data storage and backups.
Estimate: Approximately $200 to $1,000 USD/year, depending on the volume of data.
- Data Traffic (Data Transfer): Costs associated with transferring data between AWS and the internet.
Estimate: $100 to $500 USD/year, depending on the amount of data transferred.
- Additional Services (VPC, IAM, Elastic Beanstalk): Variable costs based on usage.
Estimate: Typically included in the cost of instances and storage or low-cost ($100-200 USD/year).

Total Estimate for AWS (5 years):
Total Cost (5 years): Approximately $15,000 to $30,000 USD (for small and medium-sized businesses with moderate usage).

3. Cost Savings Comparison:
On-Premise Server (5 years): $70,000 to $150,000 USD
AWS (5 years): $15,000 to $30,000 USD

Financial Comparison Conclusion:
- The AWS option offers a potential 60% to 80% reduction in total costs over 5 years, primarily due to the elimination of high upfront hardware and infrastructure costs, in addition to the flexibility and scalability offered by the pay-as-you-go model.
- These savings can be even greater if we consider the agility in implementation, ease of maintenance and gains in productivity for the IT team, which will no longer need to worry about the physical management of the servers.

This plan should provide an efficient, secure and lower-cost infrastructure for Lecter Industries.

Signature of the Project Manager: 
Jonas Fernando Schuh
