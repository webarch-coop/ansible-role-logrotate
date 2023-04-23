# Webarchitects logrotate Ansible Role

[![pipeline status](https://git.coop/webarch/logrotate/badges/master/pipeline.svg)](https://git.coop/webarch/logrotate/-/commits/master)

An Ansible role to configure logrotate on Debian and Ubuntu.

Currently all this role does is check the configuration.

## Role Variables

See the [defaults/main.yml](defaults/main.yml) file for the default variables, the [vars/main.yml](vars/main.yml) file for the preset variables and the [meta/argument_specs.yml](meta/argument_specs.yml) file for the variable specification.

### logrotate

A boolean, when `logrotate` is `true` the tasks in this role will be run.

### logrotate_verify

A boolean, verify variables that start with `logrotate_`.

## Repository

The primary URL of this repo is [`https://git.coop/webarch/logrotate`](https://git.coop/webarch/logrotate) however it is also [mirrored to GitHub](https://github.com/webarch-coop/ansible-role-logrotate) and [available via Ansible Galaxy](https://galaxy.ansible.com/chriscroome/logrotate).

If you use this role please use a tagged release, see [the release notes](https://git.coop/webarch/logrotate/-/releases).

## Copyright

Copyright 2023 Chris Croome, &lt;[chris@webarchitects.co.uk](mailto:chris@webarchitects.co.uk)&gt;.

This role is released under [the same terms as Ansible itself](https://github.com/ansible/ansible/blob/devel/COPYING), the [GNU GPLv3](LICENSE).
