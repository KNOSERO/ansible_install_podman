# Ansible Install Podman
Script for installing podman in Ansible

## Example

```yaml
- name: Install Podman
  hosts: localhost
  become: true

  tasks:
    - name: Install Podman
      include_tasks: ./task/ansible_install_podman/playbook.yml 
```