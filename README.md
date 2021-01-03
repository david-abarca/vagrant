# Vagrant
Private Vagrant for provisioning environments with Virtualbox and VMware.

## Prerequisites

Before being able to run any of the vagrant environments you need to specify the following environment variables in your local host.

Add these to your shell so you always have then on startup and ready for usage.
```
export VAGRANT_ANSIBLE_CONFIG='~/projects/dev_ansible/ansible.cfg'
export VAGRANT_ANSIBLE_INVENTORY='~/projects/dev_ansible/inventory.yml'
```

Last but not least you need an Ansible environment, for eg. the Ansible repo I have on my profile.

### Summary
- Environment variables set
- Ansible environment for provision (optional, check main.yml within vagrant env.)
## Inventory
template-vb.local, 172.20.100.10, dnsmasq
