# Devopsible

> I just need something to prepare my working environments like configs, tools, completions, shell and more, Then Devopsible has born.

Devopsible is Ansible Role To install and configure most popular devops tools with all option your need within one configuration file.

## Usage

### devopsible.yaml

```yaml
hosts: devopsible
vars:

roles:
  - pepodev.devopsible
```

### inventory.ini

```ini
[all]
me ansible_host=127.0.0.1 ansible_user=ubuntu

[devopsible]
me
```

### Run anisble-playbook

```sh
ansible-playbook -i inventory.ini devopsible.yaml -b
```

## Contribruted

Welcome for all contriburter to add feature and improve this roles.
