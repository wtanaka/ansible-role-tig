[![Build Status](https://travis-ci.org/wtanaka/ansible-role-tig.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-tig)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-tig.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-tig)

wtanaka.tig
===========

Installs tig

Tig is an ncurses-based text-mode interface for git. It functions
mainly as a Git repository browser, but can also assist in staging
changes for commit at chunk level and act as a pager for output from
various Git commands.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: wtanaka.tig

### `tig_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "tig" is already in
he path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
