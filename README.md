# Ansible Role: mssql

[![Lint](https://github.com/dcjulian29/ansible-role-mssql/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-mssql/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-mssql.svg)](https://github.com/dcjulian29/ansible-role-mssql/issues)

This an Ansible role to install Microsoft SQL Server.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.mssql
  src: https://github.com/dcjulian29/ansible-role-mssql.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
