# ansible-role-terraform

Installs [Terraform](https://www.terraform.io).

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

Time till apt cache will be refreshed.

```YAML
apt_cache_valid_time: 3600
```

## Dependencies

None.

## Example Playbook

```yml
- hosts: all
  roles:
    - ansible-role-terraform
```

## License

MIT
