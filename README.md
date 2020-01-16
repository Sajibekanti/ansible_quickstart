# ansible_quickstart
### Commands to run the playbooks:
#### Playbooks #1,2,3:
```
ansible-playbook -i inv web-0[1-3]*.yml 
```

#### Playbooks #4,5,6:
```
ansible-playbook -i inv web-0[4-6]*.yml -e "target_service=httpd"
```
