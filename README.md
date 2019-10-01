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
4. Upload `AEM_6.5_Quickstart.jar` and `license.properties` into `/home/vagrant/`
5. Provision your machine
    ```
    vagrant reload --provision
    ```

## Other links

## TO DO
-[ ] add dependencies 

## License
Copyright (c) We Are Interactive under the MIT license.