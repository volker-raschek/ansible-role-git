# git-role

[![Build Status](https://drone.cryptic.systems/api/badges/volker.raschek/git-role/status.svg)](https://drone.cryptic.systems/volker.raschek/git-role)
[![Ansible Role](https://img.shields.io/ansible/role/d/58759)](https://galaxy.ansible.com/volker_raschek/git)

With following role can be git for users configured.

## Installation

```bash
ansible-galaxy install volker_raschek.git
```

## Supported distributions

- Arch Linux
- Rocky Linux 8
- Ubuntu 20.04

## Features

- Installing git
- Configuring git
  - User specific configuration
  - User specific git commit message
  - User specific git ignore list

## Configuring

In the default directory are examples how to configure `git`. Copy the
defaults into your `host_vars` or `group_vars` and adapt the examples.
