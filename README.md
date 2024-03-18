# ansible-apps_xfce_desktop

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_xfce_desktop-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_xfce_desktop)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_xfce_desktop.svg)](https://github.com/lotusnoir/ansible-apps_xfce_desktop/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_xfce_desktop?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_xfce_desktop)
[![downloads](https://img.shields.io/ansible/role/d/56107)](https://galaxy.ansible.com/lotusnoir/apps_xfce_desktop)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56107)](https://galaxy.ansible.com/lotusnoir/apps_xfce_desktop)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install the graphic desktop interface xfce.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_xfce_desktop
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_xfce_desktop


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
