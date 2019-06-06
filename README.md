# Zabbix-Template-HTTPS-Certificates

Zabbix 4.0+ required.<br>
Creates items for each url via discovery script.<br>
Script is in template, no need to copy to server.<br>

To add\delete url to the check list modify this part of the script(in template):
<pre>
urls=(
    yandex.ru
    google.com
)
</pre>
