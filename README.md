# ansible-unbound

Installs [Unbound][] on Debian-based systems.

Please see [defaults/main.yml](defaults/main.yml) for default values.

[unbound]: https://unbound.docs.nlnetlabs.nl/

## Unbound Exporter

If `unbound_exporter_address` is defined (i.e. `address:port`), a Prometheus
[unbound_exporter][] is installed.

[unbound_exporter]: https://github.com/letsencrypt/unbound_exporter

## License

GNU General Public License v3 or later (GPLv3+)
