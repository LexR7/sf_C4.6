Практическая работа С4.6
Приведены примеры используемые конфигурационных файлов.
Компоненты размещены на двух серверах:
1. Сервер vm1.local
На нем установлены elasticsearch, logstash, kibana
2. Сервер sfca.local
На нем установлены filebeat, nginx
Логи nginx обрабатываются как модулем filebeat, так и через rsyslog передаются на logstash на сервере vm1.local
С этого же сервера через rsyslog направляется 
