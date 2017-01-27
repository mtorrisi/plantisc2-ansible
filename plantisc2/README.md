Role Name
=========

A role to deploy the Plantisc2 application and prepare the dependent services for it.

Requirements
------------

Some system services are installed and configured :

  * mysql server
  * nginx server
  * php CGI gateway.

Role Variables
--------------

Some variables are kept in `vars/main.yml`. Most are in `defaults/main.yml`

Dependencies
------------

none yet.


Example Playbook
----------------

In order to use the role, simply use the playbook :

```
    - hosts: servers
      roles:
         - { role: plantisc2, become: true}
```
License
-------

Apache-2.0

Author Information
------------------

Original Author: Mario Torrisi (INFN, Catania) @mtorrisi

Contributing Authors:

  * Bruce Becker (CSIR Meraka Institute) @brucellino
