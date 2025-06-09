# Kali Linux Ansible

Ansible playbook to streamline the customization of a fresh Kali Linux installation. Much of the setup is personal preference, so you may find that you want to add your own tasks and roels as your needs evolve.

<!-- Add Table of Contents below -->
## Table of Contents

- [Kali Linux Ansible](#kali-linux-ansible)
- [Setup](#setup)
- [Requirements](#requirements)

## Requirements

- Ansible 2.9 or higher

To install Ansible on Kali Linux, run:
```bash
sudo apt install ansible
```

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/sam-redman/kali-linux-ansible.git
   ```

2. Change into the project directory:
   ```bash
   cd kali-linux-ansible
   ```

3. Run the playbook:
   ```bash
   ansible-playbook playbooks/kali-setup.yml
   ```