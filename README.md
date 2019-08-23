# ==== Nexus docker container ====
Nexus repository at (AWS)

## Installation Guide
- Connect to aws bastion host first
 - configure hosts file inside inventory firectory accordingly
 - execute the command:
   ansible-playbook -i inventory/hosts ansible-playbook.yml

### Pre-requisites
We'll need the following installed in our host machine:
- [Docker](https://www.docker.com/get-docker)
- [Ansible](https://www.ansible.com/)
- [ansible-galaxy](ansible-galaxy install geeringguy.apache)


- OBS:
  - In case apache version change, please check the file ssl.conf and remove vhosts from that file.

[Vicente Fontanella © 2019]
