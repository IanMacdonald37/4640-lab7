ssh-keygen -t ed25519 -f aws

ansible-playbook -i ./inventory/hosts.yml playbook.yml

ansible-playbook --syntax-check playbook.yml
