# Ansible Role for GitLab CE

## 4.7.0 - TBC

### Major Changes

  - Install Python package with `pipx`
  - Simplify Python dependency with system packages
  - Support RHEL 8 with Molecule
  - Support RHEL 7 with Molecule
  - Remove CentOS 8 support
  - Improve HTTP transparent proxy support
  - Support CentOS 8 Stream
  - Support openSUSE Tumbleweed
  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt
  - Migrate from Travis CI to GitLab CI
  - Rename role as `ansible-role-gitlab_ce`
  - Install `python-gitlab`
  - Support Fedora 33
  - Remove Fedora 32 support
  - Support Ubuntu 20.10
  - Remove redundant tags from tasks

## 4.5.0 - 2020-08-26

### Major Changes

  - Upgrade minimal Ansible Lint support to 4.3.2
  - Upgrade Travis CI test as Ubuntu Focal based
  - Upgrade minimal Ansible support to 2.10.0
  - Support openSUSE Leap 15.2
  - Improve Docker image support

## 4.4.0 - 2020-07-14

  - Ininitial release for Ansible 2.9 or higher
  - This role was designed for:
      - Ubuntu 18.04/20.04
      - RHEL/CentOS 7/8
      - openSUSE Leap 15.1
      - Debian 10
      - Fedora 32
