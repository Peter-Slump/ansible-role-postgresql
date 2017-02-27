# Ansible role PosgreSQL

Version: 0.0.2

Supported OS: Ubuntu

Ansible role PosgreSQL

- Configures Monit monitoring

## Role variables
```
postgresql_version: "9.4"
postgresql_listen_addresses: localhost
postgresql_port: 5432
postgresql_data_directory: /var/lib/postgresql/{{ postgresql_version }}/main
```

## Example
```
- hosts: all
  roles:
   - role: postgresql
     postgresql_version: 9.3
```
