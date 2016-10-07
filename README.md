# bundlewrap-bundles-fedora

This repo provides an overview for my public [bundlewrap](http://bundlewrap.org/) bundles.

Most of the bundles have been tested with Fedora 24 as well as Fedberry 24, a derivate to run Fedora on a Raspberry Pi.

Most of the bundles can work with CentOS or any other RHEL derivate as well.
But tweaks may be required. For example the package `vnstat` is not available in the CentOS Repos. EPEL must be installed before the vnstat bundle can be used.

## Bundles

* Base OS and services
  * [hostname](https://github.com/rullmann/bundlewrap-hostname)
  * [Base packages](https://github.com/rullmann/bundlewrap-packages-base)
  * [Development packages](https://github.com/rullmann/bundlewrap-packages-development)
  * [yum](https://github.com/rullmann/bundlewrap-yum)

* Base OS extensions
  * [firewalld](https://github.com/rullmann/bundlewrap-firewalld)
  * [Fish shell](https://github.com/rullmann/bundlewrap-fish)
  * [htop](https://github.com/rullmann/bundlewrap-htop)
  * [OpenSSH server](https://github.com/rullmann/bundlewrap-openssh)
  * [python](https://github.com/rullmann/bundlewrap-python)
  * [vnstat](https://github.com/rullmann/bundlewrap-vnstat)

* Additional services
  * [NFS Server](https://github.com/rullmann/bundlewrap-nfs-server)
  * [NTP Client](https://github.com/rullmann/bundlewrap-ntp)

* User management
  * [users](https://github.com/rullmann/bundlewrap-users)

### Pick your bundles!

  git submodule add git@github.com:rullmann/bundlewrap-firewalld.git bundles/firewalld
  git submodule add git@github.com:rullmann/bundlewrap-fish.git bundles/fish
  git submodule add git@github.com:rullmann/bundlewrap-hostname.git bundles/hostname
  git submodule add git@github.com:rullmann/bundlewrap-htop.git bundles/htop
  git submodule add git@github.com:rullmann/bundlewrap-nfs-server.git bundles/nfs-server
  git submodule add git@github.com:rullmann/bundlewrap-ntp.git bundles/ntp
  git submodule add git@github.com:rullmann/bundlewrap-openssh.git bundles/openssh
  git submodule add git@github.com:rullmann/bundlewrap-packages-base.git bundles/packages-base
  git submodule add git@github.com:rullmann/bundlewrap-packages-development.git bundles/packages-development
  git submodule add git@github.com:rullmann/bundlewrap-python.git bundles/python
  git submodule add git@github.com:rullmann/bundlewrap-users.git bundles/users
  git submodule add git@github.com:rullmann/bundlewrap-vnstat.git bundles/vnstat
  git submodule add git@github.com:rullmann/bundlewrap-yum.git bundles/yum
