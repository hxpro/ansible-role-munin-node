hxpro.munin-node
===============

Munin node


Role Variables
--------------

| Variable              | Default value
|---                    |---
| munin_node_allow      | [127.0.0.1/32]

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: hxpro.munin-node
           munin_node_allow:
             - 192.168.0.1/32

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
