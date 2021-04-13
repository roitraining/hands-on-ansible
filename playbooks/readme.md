# Cheat Sheet

## Use Ping Playbook
```
ansible-playbook playbook-ping.yaml -i inventory.txt 
```

## Use Script Playbook
```
ansible-playbook playbook-script.yaml -i inventory.txt 
```

## Use Apt Playbook (Note the --ask-become-pass parameter)
```
ansible-playbook playbook-apt.yaml -i inventory.txt --ask-become-pass
```