# Secure-Cloud-Infrastructure-Project
Project Description: Cloud Infrastructure for XCorp Red Team

Introduction:
This project aims to create a highly available web server infrastructure on Azure for XCorp’s Red Team, facilitating testing and training activities.

Cloud Setup Overview:
The cloud setup includes an Azure Resource Group that houses a Virtual Network (VNet) with specified IP address ranges and subnets. Within this environment, multiple Virtual Machines (VMs) are deployed to host Damn Vulnerable Web Application (DVWA), ensuring redundancy and load balancing.

Components and Functionality:
The infrastructure leverages Docker containers deployed on each VM to encapsulate and manage DVWA instances efficiently. Ansible automation is integrated through an Ansible Jump Box, streamlining configuration management across the infrastructure.

Traffic and Security:
Traffic management is handled by a Load Balancer, directing HTTP requests to the DVWA instances. Strict security measures are implemented using configured security groups to control SSH access, ensuring secure administrative interactions within the environment.

Conclusion and Significance:
In summary, this project establishes a robust, scalable web server infrastructure that enhances XCorp’s capabilities for testing and training scenarios. By incorporating Docker for containerization and Ansible for automation, the solution ensures operational efficiency and flexibility in managing the cloud environment.