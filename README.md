# Docker Role for RHEL / CentOS 9

## Description
This role installs the latest Docker CE on RHEL/CentOS 9 and ensures the Docker service is started and enabled.

## Variable
| docker version | latest | Version of Docker CE to install |

## Usage
```yaml
- hosts: servers
  become: yes
  roles:
    - docker
