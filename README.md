# Ansible Role: ansible-apps_xfce_desktop


## Description

[![Build Status](https://travis-ci.com/lotusnoir/ansible-apps_xfce_desktop.svg?branch=master)](https://travis-ci.com/lotusnoir/ansible-apps_xfce_desktop)[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen)](https://opensource.org/licenses/Apache-2.0)[![Ansible Role](https://img.shields.io/badge/ansible%20role-apps__xfce_desktop-blue)](https://galaxy.ansible.com/lotusnoir/ansible-apps_xfce_desktop/)[![GitHub tag](https://img.shields.io/badge/version-latest-blue)](https://github.com/lotusnoir/ansible-apps_xfce_desktop/tags)

Deploy [xfce_desktop](https://gitlab.com/alxrem/prometheus-logstash-exporter) using ansible.


## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `xfce4_packages` | [xfce4, task-xfce-desktop] | xfce desktop packages |
| `xfce4_extra_packages` | :9114 | Prometheus endpoint |
| `xfce4_login_manager_package` | info | log level  |
| `xfce4_login_manager_service` | info | log level  |

## Examples

	---
	- hosts: apps_xfce_desktop
	  become: yesxfce4_packages:
	  become_method: sudo
	  gather_facts: yes
	  roles:
	    - role: ansible-apps_xfce_desktop
	  environment: 
	    http_proxy: "{{ http_proxy }}"
	    https_proxy: "{{ https_proxy }}"
	    no_proxy: "{{ no_proxy }}


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.
