# PostgreSQL 18 Three-Node Cluster Automation

Ansible automation project for deploying and managing a PostgreSQL 18 three-node cluster on AlmaLinux.

## Architecture

- dblab01 - Primary
- dblab02 - Standby
- dblab03 - Standby

## Technology Stack

- PostgreSQL 18
- AlmaLinux 10.1
- Ansible
- Vagrant
- VMware Desktop

## Automation Workflow

1. Preflight Validation
2. Environment Cleanup
3. OS Preparation
4. PostgreSQL RPM Installation
5. Storage Configuration
6. PostgreSQL Initialization
7. Primary Configuration
8. Standby Configuration
9. Cluster Validation

## Current Status

### Completed

- Three-node infrastructure
- Ansible inventory
- SSH connectivity
- Privilege escalation
- PostgreSQL environment preflight validation

### In Progress

- Automated PostgreSQL cleanup
