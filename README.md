# Ansible Role: Percona

Ansible playbook to install Percona Server on Debian/Ubuntu servers.
Adapted from https://github.com/hpcloud-mon/ansible-percona

## Requirements

Ansible >= 2.5 and <= 2.8. 
See https://github.com/artefactual-labs/ansible-percona/issues/41

## Role Variables

Check the file defaults/main.yml for the role defaults.

As a minimum, override the variable `mysql_root_password` in your playbook as
it is set to a weak value by default.


## License

MIT / BSD
