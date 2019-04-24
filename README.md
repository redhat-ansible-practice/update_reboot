Update & Reboot
=========

This role updates all the rpms in a system and reboots using the new ansible reboot action plugin. This role can be used in combination with numerous roles.

Requirements
------------

 Ansible 2.7 installed on the controller.

Role Variables
--------------

N/A

Dependencies
------------


Example Playbook
----------------

    - hosts: all
      roles:
         - update_reboot
         - hardening
         - nginx
         - postgresql
         - app

License
-------

GPLv3

Author Information
------------------

