# Ansible role - mto79.system.cockpit

This is an Ansible role to install and configure cockpit.
Include more information about cockpit in this section.

## Table of Contents

- [Ansible role - mto79.system.cockpit](#ansible-role---mto79systemcockpit)
  - [Table of Contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Role variables](#role-variables)
    - [Setup](#setup)
    - [Upstream](#upstream)
  - [Example Playbook](#example-playbook)

## [Requirements](#requirements)

- The minimum version of Ansible required is 2.12.0.
- The minimum version of Jinja template 2.11.3

## [Role variables](#role-variables)

### Setup

| Variable | Type | Default | Description |
| -------- | ---- | ------- | ----------- |

### Upstream

| Variable | Type | Default | Description |
| -------- | ---- | ------- | ----------- |

## [Example Playbook](#example-playbook)

Refer to the following example:

```yaml
    - hosts: "servers"
      roles:
        - role: "mto79.cloudfare.dns"
          vars:
            __role_action: "setup"
          tags: ['cloudfare', 'cloudfare-dns']
```
