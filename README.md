# Zabbix-Template-HTTPS-Certificates

Creates items for each url via discovery script.
Script is in template, no need to copy to server.

To add\delete url to the check list modify this part of script:
<pre>
urls=(
    yandex.ru
    google.com
)
</pre>
