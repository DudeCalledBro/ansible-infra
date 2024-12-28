# Ansible Infrastructure

[![CI](https://github.com/DudeCalledBro/ansible-infra/actions/workflows/ci.yml/badge.svg)](https://github.com/DudeCalledBro/ansible-infra/actions/workflows/ci.yml)

This repository serves as a comprehensive collection of common Ansible playbooks, roles, and collections tailored for efficient server administration. It provides reusable automation scripts that streamline the management, configuration, and deployment of server environments.

With a focus on best practices, this repository aims to simplify routine tasks, enhance system security, and improve operational efficiency. Whether you're managing a single server or an extensive infrastructure, you'll find valuable resources to help automate and optimize your server administration workflows.

## Prerequisites

Install required Python packages using pip3:

```bash
pip3 install -r requirements.txt
```

This command will install all necessary Python dependencies specified in the requirements.txt file, ensuring the project has the correct libraries and versions for proper execution.

## Collections and Roles

To install Ansible Galaxy roles and collections:

```bash
ansible-galaxy role install -r requirements.yml -p roles
ansible-galaxy collection install -r requirements.yml -p collections
```

Most of the Ansible requirements are maintained by me, your friendly neighborhood sysadmin. Feel free to install additional roles if you’re feeling adventurous! Just remember: with great power comes great responsibility and maybe a few surprises along the way!

## License

Copyright © 2024 Niclas Spreng

Licensed under the [MIT license](LICENSE).
