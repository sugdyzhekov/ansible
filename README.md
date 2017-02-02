About
=====

Ansible docker image based on official python 2.7-alpine image. Alpine version is 3.4

How to use
==========

Put your playbook to current directory and run:
```
docker run -ti -v $(pwd):/workbench  ansible:2.2-alpine playbook.yml
```

Specific ansible version
========================

Edit `Dockerfile` to set specific `ansible` version: 
```
ENV ansible_version v2.2.1.0-1
```

Access
======
SSH clone URL: ssh://git@git-hosting.labs.intellij.net/it-ansible-alpine.git
HTTPS clone URL: https://git-hosting.labs.intellij.net/it-ansible-alpine.git

Develop with pleasure!
