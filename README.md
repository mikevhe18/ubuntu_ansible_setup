## Installation
Ansible :
```
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt-get install ansible
sudo apt-get install git
```
For more information [Installing Ansible On Ubuntu](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)

Run `ansible-playbook main.yml --ask-become-pass` and enter your sudo password to run the playbook
