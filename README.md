# Docker Container Deployment with Ansible

This repository contains an Ansible playbook and instructions for deploying Docker containers, specifically targeting Apache services, and configuring networking for accessibility from the host machine.

## Objective

The objective of this assessment is to evaluate the understanding and practical application of deploying Docker containers using Ansible. This involves:

- Creating a template file and storing it in GitHub.
- Using Ansible to deploy Docker containers based on provided specifications.
- Deploying a Docker container running Apache service with a static web page.
- Configuring the container to allow network communication and verifying accessibility from the host machine.

## Requirements

- GitHub Repository
- Docker installed on the target machine(s)
- Ansible installed on the control machine

## PART A: Creating Ansible Playbook

### Task 1: GitHub Repository Setup

- Create a public GitHub repository for this assessment.
- Initialize the repository with a README.md file explaining the purpose of the repository and providing any necessary instructions.
- Store the Ansible playbook in GitHub.

### Task 2: Deploying Apache Docker Container

- Define a task to deploy an Apache Docker container:
  - Use the `docker_container` Ansible module to run a Docker container with Apache image.

### Task 3: Configure Networking for Apache Container

- Define a task to configure networking for the Apache Docker container:
  - Set up the container to run on `172.168.10.0/30` subnet.
  - Ensure the Apache service is accessible from the host machine.

## PART B: Ansible Playbook (`docker_deploy.yml`)

You can find the Ansible playbook for this assessment in the `docker_deploy.yml` file.

## Network Diagram

A network diagram illustrating the relationships between the GitHub repository, host machine, and Apache Docker container running on the `172.168.10.0/30` subnet is provided.

---

For any inquiries or assistance, please drop a message.

**Note:** Make sure Docker is installed on the target machine(s) and Ansible is installed on the control machine before executing the playbook.
