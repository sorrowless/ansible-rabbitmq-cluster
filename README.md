## AndrewGodGivens /RabbitMQ_HA_cluster
============

An Ansible role which installs and configures RabbitMQ HA cluster on Linux

============

## Requirements

Ansible 2.8+

============

## Role Variables

You can see all vars in defaults/main.yml vars file.

## Example Playbook

```yaml
- name: Ensure RabbitMQ_HA_cluster
  hosts: rabbitmq
  remote_user: root

  roles:
    - RabbitMQ_HA_cluster

```
