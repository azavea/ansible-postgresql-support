# ansible-postgresql-support

An Ansible role for installing libraries that support the following PostgreSQL Ansible modules:

- [postgresql_db](http://docs.ansible.com/postgresql_db_module.html)
- [postgresql_user](http://docs.ansible.com/postgresql_user_module.html)

## Role Variables

- `postgresql_support_libpq_version` - PostgreSQL client library version (default: `9.3.5-2.pgdg14.04+1`)
- `postgresql_support_psycopg2_version` - Psycopg2 version (default: `2.5.4`)
- `postgresql_support_repository_channel` - PostgreSQL repository channel (default: `main`)

## Example Playbook

See the [examples](./examples/) directory.
