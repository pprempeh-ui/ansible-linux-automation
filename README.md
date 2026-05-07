# Linux Server Automation with Ansible

## Overview
This project demonstrates infrastructure automation using Ansible on Red Hat Enterprise Linux systems.

## Features
- LVM storage provisioning using volume groups and logical volumes
- XFS file system creation and persistent mounting
- User and group management
- Secure password handling with Ansible Vault
- Passwordless sudo configuration
- Network configuration using Red Hat system roles
- Automated log rotation using cron jobs
- Modular playbooks with centralized orchestration

## Technologies Used
- Ansible
- Red Hat Enterprise Linux
- YAML
- LVM
- Ansible Vault
- Red Hat System Roles
- Cron

## Playbooks Created
- `storage.yml` - Configures LVM storage and mounts
- `dev-users.yml` - Creates users and configures sudo access
- `network.yml` - Configures network interfaces
- `log-rotate.yml` - Sets up cron jobs
- `site.yml` - Runs all playbooks in order

## Skills Demonstrated
- Infrastructure as Code
- Linux system administration
- Automation and configuration management
- Secure user provisioning
- Storage management
- Network configuration
- Scheduled system maintenance
