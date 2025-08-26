# Ansible Install Podman
Script for installing podman in Ansible

## Example

```yaml
- name: Install Podman
  hosts: localhost
  become: true

  tasks:
    - name: Install Terraform
      include_tasks: ./task/ansible_install_podman/playbook.yml 
```