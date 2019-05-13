# Ansible Role: Fail2Ban

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-fail2ban.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-fail2ban)

Installs and configures [Fail2Ban](https://www.fail2ban.org/) on Linux systems via an Ansible role.

The SSH jail is the only jail that is configurable at the moment and is enabled by default.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/fail2ban).

## Requirements

If running against a RedHat based system then you'll need to have the Epel repo installed.

I suggest running the Ansible role designed by [Geerlingguy](https://github.com/geerlingguy/ansible-role-repo-epel) before this role if you don't already have it installed.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## License

MIT
