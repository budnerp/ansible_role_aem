# Ansible role for Adobe Experience Manager
Ansible role for Adobe Experience Manager installation for CentOS 7
   
## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_aem.git ansible_role_aem
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_aem
    [...]
    ```
5. Provision your machine
    ```
    vagrant reload --provision
    ```
6. Log into the VM
    ```
    vagrant ssh
    ```
7. To start AEM author instance execute:
    ```
    sudo /opt/aem/author/crx-quickstart/bin/start
    ```
    To start AEM publish instance:
    ```
    sudo /opt/aem/publish/crx-quickstart/bin/start
    ```
   
## Other links

## TO DO
-[ ] add dependencies 

## License
Copyright (c) We Are Interactive under the MIT license.