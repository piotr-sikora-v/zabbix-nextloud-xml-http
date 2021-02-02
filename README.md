# zabbix-nextcloud-xml-http
Zabbix monitoring for Nextcloud via http agent xml with dependent items

1/ Import zabbix-nextcloud-xml-http-template.xml to zabbix templates
2/ Add template to host
3/ Create user in NextCloud with admin privilages
4/ Set host macros in zabbix: 
{$NCUSER} - Username in Nextcloud
{$NCPW} - Password in Nextcloud 
{$NCHOST} - host to connect without any prefix eg. "my.nextcloud.com"
