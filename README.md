# Odoo Installation using ansible 

It's a demonstration how to install Odoo using ansible. It supports Odoo version 10 

1. You have to change your ip address of machines( or containers) that placed in inventory file 
```
[dbservers]
Your ip @
``` 
2. start playbook using this command:
```
ansible-playbook -i inventory playbook.yml
```

    
