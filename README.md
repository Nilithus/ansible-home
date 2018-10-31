# Ansible Automation
Ansible scripts used for installing software on home servers. This is meant for personal use.

## Setup
1. copy `./ansible/hosts.dist` to `./ansible/hosts` and configure servers

## Useful links
- [Ansible Docs](https://docs.ansible.com/ansible/latest/index.html)

## Running
- To use local host file run `ansible -i ./ansible/hosts`

## Testing
Use the vagrantfile to spin up a vm and run `vagrant provision` to test out playbooks in this repo