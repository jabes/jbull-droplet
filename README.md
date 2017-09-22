# Droplet Provisioning

Server: http://www.jbull.ca

### Install

```bash
sudo apt-get install -y ansible
git clone https://github.com/jabes/jbull-droplet
ansible-galaxy install -r jbull-droplet/requirements.yml
ansible-playbook jbull-droplet/playbook.yml
```
