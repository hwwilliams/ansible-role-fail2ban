# Ansible Role: Fail2Ban

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-fail2ban.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-fail2ban)

Installs [Fail2Ban](https://www.fail2ban.org/) on Linux systems via an Ansible role.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/fail2ban).

## Requirements

If running against a RedHat based system then you'll need to have the Epel repo installed.

I've included a requirements file that will pull the Epel repo Ansible role designed by [Geerlingguy](https://github.com/geerlingguy/ansible-role-repo-epel)

```bash
ansible-galaxy install -r requirements.yml
```

## Role Variables

[defaults/main.yml](defaults/main.yml)

## License

MIT
