Update & Reboot
=========

This role updates all the packages in a system and reboots using the new ansible reboot action plugin. This role can be used in combination with numerous roles. This role uses ansible variables to indentify the OS family and use the correct package system. For example yum or apt.

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
jlozadad@redhat.com