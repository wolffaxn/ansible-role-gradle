# Ansible Role - Gradle

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/wolffaxn/ansible-role-gradle/master.svg)](https://github.com/wolffaxn/ansible-role-gradle)

## About

Installs Gradle for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    gradle_version: 3.2.1

    gradle_download_dir: /tmp
    gradle_download_cleanup: true
    gradle_install_dir: /opt

    gradle_set_gradle_home: true

## Dependencies

None.

## Example Playbook

For RHEL / CentOS

```yaml
---
- hosts: localhost
  become: true
  become_method: sudo
  remote_user: root
  roles:
    - ansible-role-gradle
```

## License

This project is licensed under the terms of the [MIT license](LICENSE).
