## Info

This will perform following acts
  - create two docker containers running and create a user and generate ssh keys for the user. 
  - add a predefined ssh key to one containers authorized keys.
  - configure ssh access from container 1 to container 2. 
  
## requirements

 - install ansible
 - dependencies mentioned in [ansible docs](http://docs.ansible.com/ansible/latest/docker_module.html)

## Execution steps

remove content in ssh folder apart from id_rsa and id_rsa.pub, replace them if you want to use different set of keys.

```
ansible-playbook -i docker.py  play.yml

```
