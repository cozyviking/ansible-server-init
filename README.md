Ansible Server Init
=========

This is a simple shell for initializing a local Ansible server instance for deploying Ansible playbooks and roles. 

Getting Started
-------

To get started, edit ansible.cfg and adjust the default variables to match your project needs. The default configuration assumes the remote user will be ec2-user with sudo escalation to root, which may need to be changed depending on your project requirements and target system configuration.

```
inventory           = ./inventory
roles_path          = ./roles/
interpreter_python  = auto_silent
remote_user         = ec2-user
sudo_user           = root
```

Compatibility
-------

This has been tested with Ansible 2.8-2.10.7.

License
-------

BSD

