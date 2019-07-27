# Ansible Role: packages

[![Build Status](https://img.shields.io/travis-ci/itigoag/ansible.packages.svg?branch=master&style=popout-square)](https://travis-ci.org/itigoag/ansible.packages) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-packages-blue.svg?style=popout-square)](https://galaxy.ansible.com/itigoag/packages) [![Ansible Role](https://img.shields.io/ansible/role/d/35019.svg?style=popout-square)](https://galaxy.ansible.com/itigoag/packages)

## Description

Installs a list of packages on the systems Centos, Ubuntu, Debian and Windows (choholatey)

## Installation

```bash
ansible-galaxy install itigoag.packages
```

## Requirements

None

## Role Variables

### packages

### packages_group

List of packages on group. See Example.

```yml
packages_group:
  firefox:
    version: latest
  7zip:
    version: latest
```

### packages_host

List of packages on host. See Example.

```yml
packages_host:
  'R.Project':
    version: latest
```

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - itigoag.packages
```

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)
- [ITIGO AG](https://www.itigo.ch)

## License

This project is under the MIT License. See the [LICENSE](licence) file for the full license text.

## Copyright

(c) 2019, Simon Bärlocher
(c) 2019, ITIGO AG
