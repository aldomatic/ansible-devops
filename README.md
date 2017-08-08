# DevOps with Ansible

Some useful playbooks and roles to get up and running. Some may find these helpful. 
These are ment to work with ubuntu/debian systems. They can easily be updated to work with other distros. 


## Userful Commands

This command will look up the hosts file based on the path supplied and will prompt for a password.
```
ansible-playbook -i PATH-TO-INVENTORY-FILE/hosts --ask-become-pass PLAYBOOK.yml
```
<br>

## Playbooks

#### Server provision (playbooks/server_provision.yml)
Below is a list of the packages installed

* build-essential
* git
* curl
* libssl-dev
* aptitude
* python2.7
* nginx
* postgresql
* libpq-dev
* python-psycopg2



#### Postgres provision (playbooks/postgres_provision.yml)
#### Github deplyoments (playbooks/github.yml)



<br>


## Roles 

 * nvm - Node Version Manager
 * yarn - Yarn Package Manager
 * postgres - Provision postgres with a new user and database



## Useful Links 
 * [Ansible Roles](http://docs.ansible.com/ansible/latest/playbooks_reuse_roles.html)
