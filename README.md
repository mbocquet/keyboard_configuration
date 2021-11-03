# keyboard_configuration

Ansible role to configure keyboard layout.

## Requirements

None.

## Role Variables

See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/keyboard_configuration.git roles/keyboard_configuration`

## Example Playbook

    - hosts: servers
      roles:
         - keyboard_configuration
or

    - hosts: servers
      roles:
         - { role: keyboard_configuration, keyboard_layout: fr }

## License

GPLv3

## Author Information

http://www.sekoya.org
