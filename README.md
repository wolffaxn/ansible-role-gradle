# Ansible Role - Gradle

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/wolffaxn/ansible-role-gradle/master/LICENSE)

Installs Gradle for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    gradle_version: 2.14

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

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

This role was created by Alexander Wolff.
