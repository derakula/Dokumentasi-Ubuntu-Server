# Dokumentasi-Ubuntu-Server

Dokumentasi Instalasi Ubuntu Server

## Static IP Setup

1. `cd /etc/netplan`
2. `sudo touch 01-netcfg.yaml`
3. `sudo nano 01-netcfg.yaml`
4. <https://www.techrepublic.com/article/how-to-configure-a-static-ip-address-in-ubuntu-server-18-04/>
5. <https://linuxize.com/post/how-to-configure-static-ip-address-on-ubuntu-18-04/>

## GUI Server

### Cockpit Install

1. Cockpit `sudo apt-get install cockpit`
2. Cek IP `ip addr show`
3. Browser: `https://ip-address:9090`

### Webmin

1. <https://www.digitalocean.com/community/tutorials/how-to-install-webmin-on-ubuntu-20-04-id>
2. <https://bobcares.com/blog/webmin-add-domain/>

#### BIND DNS

1. <https://serverspace.io/support/help/configure-bind9-dns-server-on-ubuntu/>

## Install web Service

### Apache

1. <https://phoenixnap.com/kb/how-to-install-apache-web-server-on-ubuntu-18-04>
2. `sudo service apache2 restart`

### MySQL

1. <https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04>
2. `sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf`
3. `sudo service mysql restart`

### PHP

1. <https://linuxize.com/post/how-to-install-php-on-ubuntu-20-04/>

#### PHPMyAdmin

1. <https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-20-04>

#### Composer

1. <https://www.digitalocean.com/community/tutorials/how-to-install-and-use-composer-on-ubuntu-20-04>

## Commands

### Network SpeedTest

1. `curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python -1`

## Install Oracle

1. <https://blogs.oracle.com/opal/pecl-install-prompts-explained,-with-particular-reference-to-oci8>
2. <https://www.nandaabiz.com/instalasi-oracle-client-oci8-di-ubuntu-20-04-berbasis-php-7-4/>
