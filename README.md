docker_xenial
=========

Simple Role for Installing latest Docker and Docker-Compose

**Example Play**:
```
---
- name: Install Docker
  hosts: docker
  vars:
    - docker_user: docker
  roles:
    - kontotto.docker_xenial
```

Role Variables
--------------

| parameter              | default | choices | comments                                                        |
|------------------------|---------|---------|-----------------------------------------------------------------|
| docker_user            |         |         | If docker_user is not empty, adding docker_user to docker group |
| install_docker         | yes     | yes, no |                                                                 |
| install_docker_compose | yes     | yes, no |                                                                 |


License
-------

MIT
