# keyboard-configuration

Ansible role to configure keyboard layout.

## Requirements

None.

## Role Variables

See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/keyboard-configuration.git roles/keyboard-configuration`

## Example Playbook

    - hosts: servers
      roles:
         - keyboard-configuration
or

    - hosts: servers
      roles:
         - { role: keyboard-configuration, keyboard_layout: fr }

## License

GPLv3

## Author Information

http://www.sekoya.org
