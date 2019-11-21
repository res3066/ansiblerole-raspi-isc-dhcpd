raspi-isc-dhcpd
=========

sets up isc-dhcpd on a Raspberry Pi

Requirements
------------

You should put your locally edited dhcpd.conf in {{ inventory_dir }}/host_files/{{ inventory_hostname }}.

If you don't, you'll get a default one which is about enough to get isc-dhcpd to start.  Maybe.  If you're lucky.

Role Variables
--------------

none - will be some in the next iteration or three

for your requirements.yml:

- src: https://github.com/res3066/ansiblerole-raspi-isc-dhcpd
  name: raspi-isc-dhcpd
  scm: git


Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - raspi-isc-dhcpd

License
-------

MIT

Author Information
------------------

Rob Seastrom <rs@seastrom.com>

