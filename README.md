Hammer Time
===========
Test Juju's behaviour under non-ideal conditions, such as machines rebooting,
processes dying, etc.

It uses chaos-generating code from
[Matrix](https://github.com/juju-solutions/matrix), but whereas Matrix is
designed to test charms, Hammer Time tests Juju itself.

Setup
-----
Setup is developer-oriented.  Run "make develop".  This will create a
virtualenv with Hammer Time installed as bin/hammer-time.
