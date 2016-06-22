# Ansible Role - Gradle

Installs Gradle for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    gradle:
      version: 2.14

      download_dir: /tmp
      download_cleanup: true
      install_dir: /opt

      set_gradle_home: true

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
