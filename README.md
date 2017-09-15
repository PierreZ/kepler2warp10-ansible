# kepler2warp10-ansible

```
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i production site.yml -f 15 -e 'ansible_python_interpreter=/usr/bin/python3'
ANSIBLE_HOST_KEY_CHECKING=False ansible all -i production -m ping -u debian -e 'ansible_python_interpreter=/usr/bin/python3'
ANSIBLE_HOST_KEY_CHECKING=False ansible all -i production -a "du -h .kepler" -u debian -e 'ansible_python_interpreter=/usr/bin/python3'
```