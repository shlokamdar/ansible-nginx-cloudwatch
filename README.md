## Project Overview
Configuration Management using Ansible to install Nginx and ship logs to AWS CloudWatch.

## Architecture
- 1 Ansible Control Node
- 1 Managed EC2 Node
- IAM Role for CloudWatch

## Tools Used
- Ansible
- AWS EC2
- CloudWatch Agent
- Nginx

## Steps
1. Create ansible user via user-data
2. Configure passwordless SSH
3. Run Ansible playbook
4. Verify logs in CloudWatch

## Outcome
- Automated Nginx setup
- Centralized log management

