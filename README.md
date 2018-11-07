# Ansible Role: packages

## Description

This Ansible role can be installed on Windows, Debian and CentOS.

## Installation

```bash
ansible-galaxy install itigo.packages
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| packages_group | | |
| packages_host | | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - itigoag.packages
```

## Changelog

### 1.0.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
* [ITIGO AG](https://www.itigo.ch)

## License

This project is under the MIT License. See the [LICENSE](licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher
(c) 2018, ITIGO AG