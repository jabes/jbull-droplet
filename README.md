# Droplet Setup

This [Ansible](https://www.ansible.com) playbook provisions the [jbull.ca](http://www.jbull.ca) server.

### Requirements

- Ubuntu 14.04: Pinup requires older versions of PHP and MySQL.

### How To Use

```bash
sudo add-apt-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install -y git ansible
git clone https://github.com/jabes/jbull-droplet
cd jbull-droplet
ansible-playbook playbook.yml
```
