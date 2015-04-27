# Ansible Role: Percona

Ansible playbook to install Percona Server on Debian/Ubuntu servers.

## Requirements

None.

## Role Variables

Available variables are listed below with its default values.

	mysql_root_password: reallylongpassword

Define the MySQL root password, this password will be used to create a **/root/.my.cnf** to allow root mysql connections without password

	mysql_port: 3306
	mysql_bind_address: 0.0.0.0

Define port and bind address for MySQL connections

	mysql_max_allowed_packet: 16M
	mysql_key_buffer: 16M
	mysql_thread_stack: 192K
	mysql_cache_size: 8

Various other settings are available in defaults/main.yml

## License

MIT / BSD
