# Ansible Role: Percona

Ansible playbook to install Percona Server on Debian/Ubuntu servers.
Adapted from https://github.com/hpcloud-mon/ansible-percona

## Requirements

None.

## Role Variables

Check the file defaults/main.yml for the role defaults.

As a minimum, override the variable `mysql_root_password` in your playbook as
it is set to a weak value by default.


## License

MIT / BSD
