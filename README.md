# MariaDB Server 10.02
## The FreeBSD port of MariaDB Server 10.02
## mariadb102-server-freebsd

FreeBSD deprecated mariadb102-server and it just so happens to be the one that works best for me. This is the latest 10.02 revision straight from FreeBSD Ports SVN.

## Install - Use all default values when prompted
```
portsnap fetch
portsnap extract
portsnap update
cd /usr/ports/databases/
git clone https://github.com/biondizzle/mariadb102-server-freebsd.git
git clone https://github.com/biondizzle/mariadb102-client-freebsd.git
mv mariadb102-server-freebsd mariadb102-server
mv mariadb102-client-freebsd mariadb102-client
cd mariadb102-server
make install clean
```
