# jenkins-ansible
This repo will help you to setup
1. jenkins
2. nginx will reverseproxy and serve jenkins from port 8080
3. secuity will be enabled with deafult user admin and password admin

## Installation of dependent roles
```bash
ansible-galaxy install -r requirements.yaml
```

## steps to run the playbook to setup
```bash
ansible-playbook -i inventories/dev installJenkins.yml
```
