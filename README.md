![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_ntp/workflows/Ansible%20Lint/badge.svg)

install_ntp
=========

Install the ntp package.

Requirements
------------

None.

Role Variables
--------------

`ntp_package`: Name of the package containing ntp. Default value is `ntp`.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.install_ntp'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
