ansible-playbook -i inventory rollout_os_config.yml


Quick Notes
=========

- yum remove in shall script, moved to packages modules
  -> if some packages where installed previously, the "yum erase" will not remove all packages, which have been installed as dependencies
      --> for example "samba-common-tools"

OPEN: Should such packages be considered too ?
OPEN: What about CIS Benchmarking 

- CIS.conf is created and disbales some modules 

OPEN: what about CIS benchmarks, not all suggested modules are disabled.

- SSHD two settings have been done
OPEN: other settings as CIS recommends, are not set