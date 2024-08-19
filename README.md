# Secure-Cloud-Infrastructure-Deployment
Project Description: Azure-Based Cloud Infrastructure for XCorp Red Team

Introduction
This project focuses on building a highly available and secure cloud infrastructure on Azure for XCorp’s Red Team to conduct testing and training activities. The environment is designed with redundancy, load balancing, and automation to ensure efficient and reliable operations.

Cloud Setup Overview
- Azure Resource Group: Contains all infrastructure components, including a Virtual Network (VNet) with defined IP address ranges and subnets.
- Virtual Machines (VMs): Deployed to host multiple instances of Damn Vulnerable Web Application (DVWA) across either two or three VMs for high availability.
- Ansible Jump Box: Used for centralized management and automated configuration across all VMs via Ansible playbooks.

Components and Functionality
- Docker Containers: Each VM runs DVWA encapsulated in Docker containers for easy deployment and management.
- Load Balancer: Distributes incoming HTTP traffic evenly across the DVWA instances, ensuring consistent performance and availability.

Traffic and Security
- Load Balancer: Manages traffic routing while maintaining redundancy across VMs.
- Security Groups: Configured to restrict access and control SSH traffic, ensuring secure interactions with the infrastructure.

Conclusion and Significance
This project delivers a scalable and secure cloud environment for XCorp’s Red Team, optimizing testing and training workflows. By utilizing Docker for containerization and Ansible for automated management, the setup guarantees operational flexibility and resilience, crucial for maintaining a reliable testing infrastructure.
