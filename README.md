# zabbix-check-smart

## Description

A script to monitor the SMART status of harddrives with [Zabbix](https://zabbix.com).

**Note**: Version 1.0.0 dropped the python2 support. See branch [python2](https://github.com/zabbix-deb/zabbix-check-smart/tree/python2) for the latest python2 compatible version.

## Usage

* Clone this repo and build the debian package yourself with `LANG=C debuild -us -uc -b; dh clean`
**or**
* Install it directly from @istoph's [repository](https://blog.chr.istoph.de/repository/)
**or**
* Clone this repo and install the script and config by hand

## Licence

New BSD Licence/BSD 3-Clause License (see [debian/copyright](debian/copyright))

## Template for the Zabbix frontend

A template for the Zabbix frontend can be found, as usual in our packages, in [/usr/share/doc/${package_name}/](examples/)
