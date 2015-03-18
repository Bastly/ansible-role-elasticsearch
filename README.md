# Ansible Role: Elasticsearch

An Ansible Role that installs Elasticsearch on RedHat/CentOS or Debian/Ubuntu.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - bastly.java

## Example Playbook

    - hosts: search
      roles:
        - { role: bastly.java }

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
