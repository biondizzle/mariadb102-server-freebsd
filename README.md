# MariaDB Server 10.02
## The FreeBSD port of MariaDB Server 10.02
## mariadb102-server-freebsd

FreeBSD deprecated mariadb102-serve and it just so happens to be the one that works best for me. This is the latest 10.02 revision straight from FreeBSD Ports SVN.

## Quick Install
```
git clone https://github.com/biondizzle/mariadb102-server-freebsd.git
cd mariadb102-server-freebsd
make install clean
```

## Advanced Install
```
git clone https://github.com/biondizzle/mariadb102-server-freebsd.git
cd mariadb102-server-freebsd
make config
make showconfig
make install clean
```

