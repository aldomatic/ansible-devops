# DevOps with Ansible

Some useful playbooks and roles to get up and running. Some may find these helpful. 

### Userful Commands

This command will look up the hosts file based on the path supplied and will prompt for a password.
```
ansible-playbook -i PATH-TO-INVENTORY-FILE/hosts --ask-become-pass PLAYBOOK.yml
```

### Playbooks

 * Server provision
 * Postgres Provision
 * Github deplyoment(s)


### Roles 

 * nvm - Node Version Manager
 * yarn - Yarn Package Manager
 * postgres - Provision postgres with a new user and database



### Useful Links 
 * [Ansible Roles](http://docs.ansible.com/ansible/latest/playbooks_reuse_roles.html)
