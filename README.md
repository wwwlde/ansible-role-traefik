# Ansible role for Traefik

Reusable Ansible role for Traefik (used for PoC). If you are interested in other versions or functionality, please provide patches.

## System Requirements

This role has only been tested with:

 * CentOS 7
 * Ansible version:
   * 2.9.11

## Example

```
- hosts: front-traefik
  become: yes
  become_method: sudo
  roles:
    - { role: ./roles/ansible-traefik }
```
