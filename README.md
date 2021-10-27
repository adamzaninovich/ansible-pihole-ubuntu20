# Ansible Playbook for setting up a pihole server on ubuntu 20.04

## Managing Secrets

To decrypt secrets:
``` sh
ansible-vault decrypt secrets_file.enc --vault-password-file password_file
```

To encrypt secrets:
``` sh
ansible-vault encrypt secrets_file.enc --vault-password-file password_file
```

## Managing Firewall

https://docs.ansible.com/ansible/2.7/modules/ufw_module.html
https://www.digitalocean.com/community/tutorials/ufw-essentials-common-firewall-rules-and-commands
