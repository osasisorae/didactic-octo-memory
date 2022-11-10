# didactic-octo-memory

Simple devops project to strenghten the following tools

###Tools:
Vagrant , Ansible, Docker, Docker Swarn.

### Goals:
- Provide multiple linux servers using vagrant.
- Run a playbook that automates the configuration of the above servers
- Containerize an enterprise web application
- Convert the servers to docker swarm nodes and bring up the application on the swarm


### Guide Ubuntu 20.04
## Install vagrant
```
wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list

sudo apt update && sudo apt install vagrant
```