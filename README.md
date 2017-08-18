# Ansible Role - NVM Node Version Manager

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-nvm.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-nvm)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-nvm/blob/master/defaults/main.yml)

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.nvm
      nvm_user: "root"
      nvm_version: "v0.33.2"
      nvm_node_versions:
        - "6.11.2"
        - "7.10.1"
        - "8.4.0"
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2017 by [elnebuloso](https://github.com/elnebuloso/)