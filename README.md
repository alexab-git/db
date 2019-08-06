DB role
=========
[![Build Status](https://travis-ci.org/alexab-git/db.svg?branch=master)](https://travis-ci.org/alexab-git/db)
Роль создана для установки и конфигурации СУБД Mongo для приложения reddit


Role Variables
--------------
mongo_port - порт, на котором будет слушать mongod, по умолчанию 27017
mongo_ip  - ip адрес, на котором будет слушать mongod, по умолчанию 127.0.0.1
env - окружение, по умолчанию local


Example playbook
----------------
```
- name: Configure MongoDB
  hosts: db
  become: true
  roles:
    - db
```

