# arma3server_ansible
Playbook for Arma3-Server Installation on Unix-Systems with Ansible

## Installation
First you have to install Ansible on your server. \\
After the installation you have to create a inventory-file. \\
When your server isn´t the same machine, you have to create a private-key and import you public key to your new arma server. 

## Usage 
On local machines: \\
ansible-playbook amra.yml -i <inventory_file> \\ \\
On remote machines: \\
ansible-playbook arma.yml -i <inventory_file> --privatekey=<privatekey>
