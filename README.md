# Ansible-kafka
Interswitch DevOps Challenge


Install ansible on CentOS 7
===============
ansible --version (to confirm if ansible is previously installed)
sudo yum install ansible
**if an error is received like : cannot find a valid baseurl for repo base7x86 64. then run the below:
sudo dhclient (install packages)

ansible --version (to check if its the latest version installed)
sudo yum install epel-release (to install packages)
sudo yum install ansible (install ansible again to install latest version)
ansible --version (to reconfirm the version
