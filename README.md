# bundlewrap-bundles-fedora

This repo provides an overview for my public [bundlewrap](http://bundlewrap.org/) bundles.

Most of the bundles have been tested with Fedora 24 as well as Fedberry 24, a derivate to run Fedora on a Raspberry Pi.

Most of the bundles can work with CentOS or any other RHEL derivate as well.
But tweaks may be required. For example the package `vnstat` is not available in the CentOS Repos. EPEL must be installed before the vnstat bundle can be used.

## Bundles

* Base OS and services
  * [dnf](https://github.com/rullmann/bundlewrap-dnf)
  * [hostname](https://github.com/rullmann/bundlewrap-hostname)
  * [Base packages](https://github.com/rullmann/bundlewrap-packages-base)
  * [Development packages](https://github.com/rullmann/bundlewrap-packages-development)

* Base OS extensions
  * [firewalld](https://github.com/rullmann/bundlewrap-firewalld)
  * [Fish shell](https://github.com/rullmann/bundlewrap-fish)
  * [htop](https://github.com/rullmann/bundlewrap-htop)
  * [OpenSSH server](https://github.com/rullmann/bundlewrap-openssh)
  * [python](https://github.com/rullmann/bundlewrap-python)
  * [vnstat](https://github.com/rullmann/bundlewrap-vnstat)

* Additional services
  * [collectd monitoring](https://github.com/rullmann/bundlewrap-collectd)
  * [hddtemp](https://github.com/rullmann/bundlewrap-hddtemp)
  * [Jenkins CI](https://github.com/rullmann/bundlewrap-jenkins)
  * [Let's Encrypt](https://github.com/rullmann/bundlewrap-letsencrypt)
  * [monit monitoring](https://github.com/rullmann/bundlewrap-monit)
  * [NFS Server](https://github.com/rullmann/bundlewrap-nfs-server)
  * [nginx Webserver](https://github.com/rullmann/bundlewrap-nginx)
  * [NTP Client](https://github.com/rullmann/bundlewrap-ntp)
  * [php-fpm](https://github.com/rullmann/bundlewrap-php)
  * [PostgreSQL Server](https://github.com/rullmann/bundlewrap-postgresql)
  * [TEMPer](https://github.com/rullmann/bundlewrap-temper)
  * [tt-rss](https://github.com/rullmann/bundlewrap-ttrss)

* User management
  * [users](https://github.com/rullmann/bundlewrap-users)

### Pick your bundles!

<pre>
git submodule add git@github.com:rullmann/bundlewrap-collectd.git bundles/collectd
git submodule add git@github.com:rullmann/bundlewrap-dnf.git bundles/dnf
git submodule add git@github.com:rullmann/bundlewrap-firewalld.git bundles/firewalld
git submodule add git@github.com:rullmann/bundlewrap-fish.git bundles/fish
git submodule add git@github.com:rullmann/bundlewrap-hddtemp.git bundles/hddtemp
git submodule add git@github.com:rullmann/bundlewrap-hostname.git bundles/hostname
git submodule add git@github.com:rullmann/bundlewrap-htop.git bundles/htop
git submodule add git@github.com:rullmann/bundlewrap-jenkins.git bundles/jenkins
git submodule add git@github.com:rullmann/bundlewrap-letsencrypt.git bundles/letsencrypt
git submodule add git@github.com:rullmann/bundlewrap-monit.git bundles/monit
git submodule add git@github.com:rullmann/bundlewrap-nfs-server.git bundles/nfs-server
git submodule add git@github.com:rullmann/bundlewrap-nginx.git bundles/nginx
git submodule add git@github.com:rullmann/bundlewrap-ntp.git bundles/ntp
git submodule add git@github.com:rullmann/bundlewrap-openssh.git bundles/openssh
git submodule add git@github.com:rullmann/bundlewrap-packages-base.git bundles/packages-base
git submodule add git@github.com:rullmann/bundlewrap-packages-development.git bundles/packages-development
git submodule add git@github.com:rullmann/bundlewrap-php.git bundles/php
git submodule add git@github.com:rullmann/bundlewrap-postgresql.git bundles/postgresql
git submodule add git@github.com:rullmann/bundlewrap-python.git bundles/python
git submodule add git@github.com:rullmann/bundlewrap-temper.git bundles/temper
git submodule add git@github.com:rullmann/bundlewrap-ttrss.git bundles/tt-rss
git submodule add git@github.com:rullmann/bundlewrap-users.git bundles/users
git submodule add git@github.com:rullmann/bundlewrap-vnstat.git bundles/vnstat
</pre>
