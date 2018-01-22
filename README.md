## Info

This will perform following acts
  - create two docker containers running and create a user and generate ssh keys for the user. 
  - add a predefined ssh key to one containers authorized keys.
  - configure ssh access from container 1 to container 2. 

## Execution steps

```
ansible-playbook -i docker.py  play.yml

```
