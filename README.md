# AutomationLab
IPSpace Automation Lab

The automation lab consists of a VMware Workstion with the following VMs

Linux Server (Centos)
 - Ansible
 - Sublime Text
 - Git
 - Python
 
Juniper vSRX x 3

--------------------------------------------------------

Ansible hosts file
[srx_devices]
vSRX-1 ansible_host=172.16.1.41
vSRX-2 ansible_host=172.16.1.42
vSRX-3 ansible_host=172.16.1.43

[all:vars]
#ansible_connection=local
ansible_user=admin
ansible_ssh_pass=xxxxxx
ansible_port=22

made changes from local git server
