# Ansible Role Uwsgi

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-uwsgi.svg)](https://travis-ci.org/hadenlabs/ansible-role-uwsgi)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-uwsgi.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-uwsgi)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-uwsgi.svg)](https://github.com/hadenlabs/ansible-role-uwsgi/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [uwsgi][link-uwsgi] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for uwsgi


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - uwsgi

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.uwsgi }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-uwsgi]: https://www.uwsgi.com
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
