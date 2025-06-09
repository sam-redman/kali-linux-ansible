# Kali Linux Ansible

Ansible playbook to streamline the customization of a fresh Kali Linux installation. Much of the setup is personal preference, so you may find that you want to add your own tasks and roels as your needs evolve.

<!-- Add Table of Contents below -->
## Table of Contents

- [Kali Linux Ansible](#kali-linux-ansible)
- [Setup](#setup)
- [Requirements](#requirements)
- [License](#license)


## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd kali-linux-ansible
   ```

2. Update the inventory file for local execution:
   ```ini
   [kali]
   localhost ansible_connection=local
   ```

3. Run the playbook:
   ```bash
   ansible-playbook playbooks/kali-setup.yml
   ```

## Requirements

- Ansible 2.9 or higher
- SSH access to the Kali Linux host

## License

This project is licensed under the MIT License. See the LICENSE file for details.