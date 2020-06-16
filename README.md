ansible jetbrains toolbox role
==============================

![CI](https://github.com/baztian/ansible-jetbrains-toolbox/workflows/CI/badge.svg)

Role to download, install and setup git plus associated tools.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.jetbrains_toolbox

License
-------

MIT
