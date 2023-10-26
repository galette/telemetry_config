Galette Telemetry config
========================

[Telemetry](https://github.com/galette/telemetry) configuration and overrides for Galette.

To set up:
```
$ git clone https://github.com/galette/telemetry.git
$ cd telemetry
$ mkdir projects
$ cd projects
$ git clone https://github.com/galette/telemetry_config.git galette
$ cd -
$ ln -s projects/galette/phinx_local.yml .
$ cp projects/galette/config.inc.php.dist ./config.inc.php
```

Then tune your `config.onc.php` and you're done!
