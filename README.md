ssh-keygen -t ed25519 -f aws

ansible-playbook -i ./inventory/hosts.yml playbook.yml

ansible-playbook --syntax-check playbook.yml

![image](https://github.com/user-attachments/assets/5646b4f4-0259-416c-804c-5b07acaaf6ec)
