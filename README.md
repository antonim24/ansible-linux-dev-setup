# ansible-linux-dev-setup
Ansible playbook to set up a new linux instance with all packages I use.

# How to run
1. Clone this repository
2. Cd into the cloned repository and run any of the playbooks. See Playbook usage for more.

# Playbook Usage

## Set server configuration and install packages
```bash
ansible-playbook setup-servers.yml -i inventory.yml -K
```

## Update and Patch Hosts
When you want to perform some software updates (patching), then run this playbook against your desired hosts.
```bash
ansible-playbook patch.yml -i inventory.yml -K
```
