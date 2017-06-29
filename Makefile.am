etcsysconfigdir=/etc/sysconfig
etcsysconfig_DATA=etc/sysconfig/lwes-journaller

etcinitdir=/etc/rc.d/init.d
etcinit_SCRIPTS=etc/rc.d/init.d/lwes-journaller

etccrondir=/etc/cron.d
etccron_DATA=etc/cron.d/lwes-journaller-rotate

etclogrotatedir=/etc/logrotate.d
etclogrotate_DATA=etc/logrotate.d/lwes-journaller

etcsupervisorddir=/etc/supervisord.d
etcsupervisord_DATA=etc/supervisord.d/lwes-journaller.ini

etcsystemddir=/etc/systemd/system
etcsystemd_DATA=etc/systemd/system/lwes-journaller.service

MAINTAINERCLEANFILES = COPYING INSTALL missing install-sh aclocal.m4 Makefile.in configure *.gz

EXTRA_DIST = etc

test:
