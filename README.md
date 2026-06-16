# Linux Baseline Automation

## Overview

Linux Baseline Automation is an Ansible-based infrastructure automation project designed to automate the provisioning and configuration of Red Hat Enterprise Linux systems.

The project demonstrates enterprise system administration practices including package management, user provisioning, SSH service configuration, and infrastructure automation.

## Features

- Automated package installation
- User account provisioning
- SSH service configuration
- Modular Ansible role design
- Infrastructure as Code (IaC) approach
- Reusable automation framework

## Technologies

- Red Hat Enterprise Linux
- Ansible
- Bash
- YAML
- Git
- GitHub

## Project Structure

```text
linux-baseline-automation/
│
├── inventory
├── baseline.yml
│
└── roles/
    ├── packages/
    ├── users/
    └── ssh/
```

## Example Execution

```bash
ansible-playbook -i inventory baseline.yml
```

## Skills Demonstrated

- Linux System Administration
- Configuration Management
- Infrastructure Automation
- User Management
- Service Administration
- DevOps Fundamentals
- Infrastructure as Code
