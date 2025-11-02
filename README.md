# AWS Multi-Tier Architecture Capstone Project

## 📝 Problem Statement

This project demonstrates how to design and deploy a robust, highly available AWS Multi-Tier Architecture as required for the AWS Cloud Support Associate role. The solution implements best practices for networking, database, storage, autoscaling, and resiliency.

## 🚀 Steps/Tasks

1. **Networking Setup**
    - Create a VPC with public and private subnets in multiple Availability Zones.
    - Attach Internet and NAT Gateways, and configure all required route tables and security groups.

2. **Database Layer**
    - Deploy an Amazon Aurora MySQL cluster (Multi-AZ) in private subnets.
    - Ensure proper security and backup configuration.

3. **Persistent Storage**
    - Set up Amazon EFS for scalable, shared storage with multi-AZ attachment.

4. **Application Layer and Autoscaling**
    - Create EC2 Launch Template and Application Load Balancer (ALB).
    - Set up a Target Group, health checks, and Auto Scaling Group for highly available app instances.

5. **Testing and Validation**
    - Access the deployed app via the ALB DNS name.
    - Test failover (instance stops), autoscale triggers, and connectivity across all tiers.

## 🖼️ Output

Screenshots of working architecture, application access, scaling, and failover scenarios are included for project validation.

## 📚 Learning Outcomes

- Hands-on experience with AWS VPC, EC2, RDS/Aurora, EFS, ALB, Auto Scaling.
- Deep understanding of fault tolerance, high availability, and cloud best practices.
- Ability to document, troubleshoot, and support complex AWS environments.

## 📖 References

- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [AWS Multi-Tier Architecture on AWS](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/architecting-for-the-cloud-best-practices.html)
- [Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- [Amazon Aurora Documentation](https://docs.aws.amazon.com/aurora/latest/mysql-aurora-user-guide/)

## 👤 Author

Raajarapu Suswin – AWS Cloud Support Associate Candidate

---

*This project is part of the AWS Cloud Support Associate certification training capstone.*
