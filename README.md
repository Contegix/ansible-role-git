ansible-role-git
=====================

Ansible Role to Install git from source

Currently only tested on CentOS.

## Requirements

None.

## Role Variables

	git_ver: "2.1.0"
	git_archive: https://www.kernel.org/pub/software/scm/git/git-{{ git_ver }}.tar.gz

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - { role: git }

## License

MIT / BSD

## Author Information

This role was created in 2014 by Solomon S. Gifford (sgifford@blackmesh.com) and sponsored by BlackMesh, Inc.

Credit: Inspired by https://github.com/akishin/ansible-playbooks
