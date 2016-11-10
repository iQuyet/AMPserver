# 1. AMPserver Info
a. AMPserver is a shell script on most POSIX systems. This script help you to install and configure a WebServer with: Apache, MariaDB, and PHP .
#
b. Curent OS support: CentOS 7, FreeBSD 11 .
#
# 2. Install
## a. Install Script Stable
### Install base
First: Install curl gzip 
### Download source
mkdir -p /home && cd /home && curl -o AMPserver-1.0.0.tar.gz -L https://github.com/iQuyet/AMPserver/archive/1.0.0.tar.gz
### Extract
tar -xzvf AMPserver-1.0.0.tar.gz
### Run script
sh AMPserver-1.0.0/amp_latest
### Done
#
### or Run with a commandline
mkdir -p /home && cd /home && curl -o AMPserver-1.0.0.tar.gz -L https://github.com/iQuyet/AMPserver/archive/1.0.0.tar.gz && tar -xzvf AMPserver-1.0.0.tar.gz && sh AMPserver-1.0.0/amp_latest
#
## b. Install Script Master
### Run with a commandline
mkdir -p /home && cd /home && curl -o AMPserver-master.tar.gz -L https://github.com/iQuyet/AMPserver/archive/master.tar.gz && tar -xzvf AMPserver-master.tar.gz && sh AMPserver-master/amp_latest
#
# 3. Note
login MariaDB with username: root and password: 456sql
#
# 4. Log
## 1.0.0
OS Support: CentOS 7 (Apache, MariaDB, PHP); FreeBSD 11 (Apache, MariaDB, PHP);
#