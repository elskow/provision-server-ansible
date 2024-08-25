## Personal Provisioning Tools - Ansible
This repository contains a collection of Ansible playbooks and roles that I use to provision my personal instances. The playbooks are designed to be idempotent and should be safe to run multiple times.

### Requirements
- Ansible 2.9 or later
- Python 3.6 or later
- A Unix-like operating system (macOS, Linux, etc.)

### Usage
1. Clone this repository to your local machine.
2. Configure environment variables under `env/` directory.
3. Run the playbook
```bash
ansible-playbook playbooks/main.yaml
```
4. Enjoy!