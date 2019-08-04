DB role
=========
Роль создана для установки и конфигурации СУБД Mongo для приложения reddit


Role Variables
--------------
mongo_port - порт, на котором будет слушать mongod, по умолчанию 27017
mongo_ip  - ip адрес, на котором будет слушать mongod, по умолчанию 127.0.0.1
env - окружение, по умолчанию local
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example playbook
----------------
```
- name: Configure MongoDB
  hosts: db
  become: true
  roles:
    - db
```

