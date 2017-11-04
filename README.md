Assumption: Entire Exercise in based on Ubuntu 14.04 Version
 
1.	Create a directory under home directory as projects/hands-on-ansible
copy Vagrant file into it
2.	Execute the command
vagrant up
3.	Login into control machine
vagrant ssh

Inside Control Machine, Install Ansible
 
sudo apt-get update -y
sudo apt-get install software-properties-common -y
sudo apt-add-repository ppa:ansible/ansible -y
sudo apt-get update -y
sudo apt-get install ansible -y
 
Execute playbook
/vagrant
ansible-playbook site.yml
 

