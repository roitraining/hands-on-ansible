# Files for ROI Training Hands-On Ansible Class

## To run Ansible from Google Cloud Shell run the following:
```
sudo apt install ansible -y
sudo apt install sshpass -y
```
You also need to add the following variable to you inventory.txt file, so Ansible will find the right version of Python

```
[hosts:vars]
ansible_python_interpreter=/usr/bin/python3
```