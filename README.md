# Ansible_and_JunOS
Different Ansible Playbooks with JunOS using the Juniper.junos role.

Ansible 2.5 and above work with Python 3.  Follow the below commands to install ansible using Python3.

`pip3 install ansible`

```
ansible --version | grep "python version"

python version = 3.10.5 (main, Jun 9 2022, 00:00:00) [GCC 12.1.1 20220507 (Red Hat 12.1.1-1)] (/usr/bin/python)`
```

Next, install the juniper.junos role using ansible-galaxy.

`ansible-galaxy role install juniper.junos`

The juniper.junos role has the following Modules:

- juniper_junos_table
- juniper_junos_jsnapy
- juniper_junos_facts
- juniper_junos_software
- juniper_junos_system
- juniper_junos_rpc
- juniper_junos_config
- juniper_junos_ping
- juniper_junos_pmtud
- juniper_junos_command
- juniper_junos_srx_cluster

More documentation for each can be found here:

https://junos-ansible-modules.readthedocs.io/en/2.4.3/

![](https://img.freepik.com/premium-photo/mt-fuji-cityscape-morning-japan-panorama-von-santiago-chile-mit-andenkordillere-ai-generated_585735-6001.jpg)
