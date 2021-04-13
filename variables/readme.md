# Cheat Sheet

### Using the Command Playbook 
```
ansible-playbook playbook-command.yaml -i inventory.txt
```

### Using the Line In File Playbook  
```
ansible-playbook playbook-add-line-in-file.yaml -i inventory.txt
```

To test whether it worked run:
```
cat runs.txt
```

### Using the Apt Playbook 
```
ansible-playbook playbook-apt.yaml -i inventory.txt --ask-become-pass
```