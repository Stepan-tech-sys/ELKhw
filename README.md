# Домашнее задание к занятию "`ELK`" - `Лопатников Степан`



---

### Задание 1

`Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.`

![1](https://github.com/Stepan-tech-sys/screenshots/blob/main/Screenshot%20from%202026-11-03%2022-53-20.png)


---

### Задание 2

`Установите и запустите Kibana. Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.`

![2](https://github.com/Stepan-tech-sys/screenshots/blob/main/Screenshot%20from%202026-11-03%2023-33-25.png)


---

### Задание 3

`Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.`

![3](https://github.com/Stepan-tech-sys/screenshots/blob/main/Screenshot%20from%202026-11-04%2002-45-02.png)

### Задание 4

`Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.`

![4](https://github.com/Stepan-tech-sys/screenshots/blob/main/Screenshot%20from%202026-11-07%2015-32-32.png)
![5](https://github.com/Stepan-tech-sys/screenshots/blob/main/Screenshot%20from%202026-11-07%2015-32-59.png)
