FROM tutum/mysql:5.5
MAINTAINER WiredPea <hi@wiredpea.com>

ADD my.cnf /etc/mysql/conf.d/

ADD init.sql /tmp/

ENV STARTUP_SQL /tmp/init.sql
