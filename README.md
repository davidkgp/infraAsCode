# infraAsCode
asnible scripts for my ubuntu setup

Required : Ansible 2.8.x (refer https://www.cyberciti.biz/faq/how-to-install-and-configure-latest-version-of-ansible-on-ubuntu-linux/)


ansible-playbook -i inventry.txt --ask-become-pass playbook.yml

## Properties
In case you want to set a different user than the one running the playbook in sudoers file(to prevent entering password for all sudo command),override the ansible_user property in the inventory.txt.If not set it will use the user who is running the ansible playbook
