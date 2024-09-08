# AWS Architecture for Medical SaaS

## Project Overview
This project involves designing and implementing a scalable, secure AWS architecture for a medical software-as-a-service (SaaS) company. Our goal is to transition from traditional on-premise servers to a cloud-based infrastructure using AWS services to enhance performance, reliability, and cost-efficiency.

## Team Members
- Venkata Sasank Jonnalagadda
- Phanindra Raja Varma Gadiraju
- Sai Sruthi Kalidindi

## Instructor
Carmen Taglienti

## Introduction
Traditional server setups for hosting medical applications are expensive and inflexible. Our project leverages AWS cloud services to provide a scalable, secure, and cost-effective infrastructure, enhancing the medical application's performance and reliability.

## Architecture Design
We utilize several AWS services to meet the performance and security requirements of the medical application:
- **AWS WAF** for web application firewall protection
- **AWS CloudFront** for content delivery optimization
- **AWS CloudWatch** for monitoring and logging
- **AWS IAM** for identity and access management
- **Amazon RDS** and **Amazon S3** for storage solutions
- **AWS Load Balancers** for traffic distribution
- Other AWS services to support high availability, scalability, and security.

## User Authentication Strategy
Our IAM policies include distinct groups with specific permissions to ensure the system's security and efficiency:
- **System Admins**
- **Database Admins**
- **Monitoring Teams**
- **Engineers**

## Network and Security
- **VPC Setup**: Separate VPCs for development and production environments, ensuring isolation and security.
- **Subnet Design**: Proper subnetting to optimize network performance and security.

## Business Continuity
- **Auto Scaling**: Implement auto-scaling to handle load changes dynamically without manual intervention.
- **Multi-Zone Availability**: Deployment across multiple availability zones to ensure high availability and disaster recovery.

## Security Audits
- Regular audits using AWS services like **AWS Config** and **AWS CloudTrail**.
- Continuous monitoring with AWS Guard Duty and Trusted Advisor to maintain security and compliance.

## Conclusion
Our AWS architecture is designed to support the evolving needs of a medical SaaS company, ensuring high availability, robust security, load balancing, and cost-efficiency.

## How to Contribute
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Thanks to Carmen Taglienti for guidance and insights throughout the project.
- Appreciation to all team members for their dedication and hard work.
v
