# LAMP Provisioning POC

### Requirements:

1. Vagrant
2. Ansible

### Usage:

```bash
# Start up 4 vagrant machines
vagrant up

# Provision the machines with the necessary software
ansible-playbook -i inventories/local/hosts provision.yml

# Set up WP databases and install Wordpress on each of the Application servers
ansible-playbook -i inventories/local/hosts install.yml
```
