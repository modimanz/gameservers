# Rust Server Role
Author: Morgan Massens

## Variables
See the defaults/main.yml file for variable

## Starting and Stopping Rust service
This playbook belowuses the rust role.   Limit by tags to start and stop the service
* Start
```ansbile setup-rust.yml --tags start```
* Stop
```ansbile setup-rust.yml --tags stop```
* Restart
```ansbile setup-rust.yml --tags restart```
