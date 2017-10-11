# Ansible Role: Common

## Description

Standards for the Linux and Windows servers

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| | | |
| | | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.common
```

## Changelog

### 1.2

* fix problem with selinux and reboot
* add tags support
* add become support

### 1.1

* Reboot by selinux change
* add hostname rename

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher