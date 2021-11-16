# Ansible Role: {{ cookiecutter.role_name }}

![MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/racqspace/ansible-role-{{ cookiecutter.role_name | replace("_", "-") }}/Main?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/racqspace/ansible-role-{{ cookiecutter.role_name | replace("_", "-") }}?style=flat-square)
![GitHub Release Date](https://img.shields.io/github/release-date/racqspace/ansible-role-{{ cookiecutter.role_name | replace("_", "-") }}?style=flat-square)
![Maintenance](https://img.shields.io/maintenance/yes/2022?style=flat-square)

Installing {{ cookiecutter.role_name }}.

## Role Variables

Variable Name | Default Value | Description
------------ | ------------- | -------------
{{ cookiecutter.role_name }}_cache_valid_time | 3600 | Cache update time for apt module.

## Role Usage Examples

Example for installing {{ cookiecutter.role_name }} in a dedicated namespace `{{ cookiecutter.role_name }}`.

```yaml
- hosts: all
  roles:
  - role: racqspace.{{ cookiecutter.role_name }}
```

## License

MIT

## Author Information

This role was created in 2021 by [Clemens Kaserer](https://www.ckaserer.dev/).

Contributions by:

- [@ckaserer](https://github.com/ckaserer)
