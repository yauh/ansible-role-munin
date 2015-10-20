# yauh.munin
Ansible role for setting up munin resource monitoring tool

## Requirements
SSH access to the remote machine

## Role Variables

```
munin_address: '*'
munin_port: 4949
munin_directory: munin
munin_nginx_port: 80
munin_users:
  - name: admin
    password: password
```

## Dependencies
None

## Example Playbook

```
- hosts: all
- roles:
  - { role: yauh.munin }
  -
```

## License
BSD

## TODO
[http://munin-monitoring.org/wiki/MuninConfigurationNetworkTLS](http://munin-monitoring.org/wiki/MuninConfigurationNetworkTLS)

## Author Information
Stephan Hochhaus stephan@yauh.de

[https://github.com/yauh](https://github.com/yauh)
