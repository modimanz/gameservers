# Rust Server Role
Author: Morgan Massens

## Variables
See the defaults/main.yml file for variable

## Playbook Example
```
- name: Add the Rust role to node
  include_role:
    name: gameservers/rust
  vars:
    steamcmd_user: steam
```

## Starting and Stopping Rust service
Limit by tags to start and stop the service
* Start
```ansbile setup-rust.yml --tags start```
* Stop
```ansbile setup-rust.yml --tags stop```
* Restart
```ansbile setup-rust.yml --tags restart```
