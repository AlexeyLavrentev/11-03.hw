# Домашнее задание к занятию «ELK»

### Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

### Выполнение:

<img width="637" height="273" alt="image" src="https://github.com/user-attachments/assets/756d31f6-8270-4682-8f87-9601f07989fa" />

### Задание 2. Kibana
Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

Выполнение:

<img width="1918" height="624" alt="image" src="https://github.com/user-attachments/assets/80ba509d-8fb1-4fdb-9318-f87544aef2fd" />


### Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

Выполнение:

<img width="1917" height="995" alt="image" src="https://github.com/user-attachments/assets/c1e980e1-2a26-418e-bf72-05e8432f6aa8" />


### Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

### Выполнение:

<img width="1903" height="946" alt="image" src="https://github.com/user-attachments/assets/3e8e2a43-3848-470b-9f74-1a9762bbeda5" />


