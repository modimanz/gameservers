Role Name
=========

Minecraft Server role with support for Forge or Vanilla

Requirements
------------

Patience

Role Variables
--------------

* minecraft_flavor: This should eithe be "vanillia" or "forge"
* minecraft_forge_version: The version of Forge you want to install, defaults to 25.0
* minecraft_user: minecraft (default)
* minecraft

Dependencies
------------


Example Playbook
----------------

    - hosts: minecraftservers
      roles:
        - role: ansible-minecraft
          vars:
            minecraft_eula: true
        
       

License
-------

MIT

Author Information
------------------

Mobi8