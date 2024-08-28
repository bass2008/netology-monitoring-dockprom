# Цель задания
Научиться пользоваться инструментами bugtrasing и мониторинга, чтобы понимать, каким образом можно мониторить ваши приложения и готовить логи.

### Перечислите алерты, которые настроены в Prometheus alerts.

Всего настроено 7 алертов в 3-х категориях.

1. (/etc/prometheus/alert-rules > containers):
   - jenkins_down (Firing) - Jenkins down
   - jenkins_high_cpu (Normal) - Jenkins high CPU usage
   - jenkins_high_memory (Normal) - Jenkins high memory usage

2. (/etc/prometheus/alert-rules > host):
   - high_cpu_load (Normal) - Server under high load
   - high_memory_load (Normal) - Server memory is almost full
   - high_storage_load (Normal) - Server storage is almost full

3. (/etc/prometheus/alert-rules > targets):
   - monitor_service_down (Normal) - Monitor service non-operational

### Перечислите количество dashboards в Grafana, для какого ПО они?

Docker Containers - для контейнеров docker

Docker Host - для docker хоста

Monitor Services - для prometheus

Nginx - для nginx

### Сделайте скриншот работающего dashboards docker containers grafana, перечислите метрики, которые там есть
CPU Load

CPU Cores

Memory Load

Used Memory

Storage Load

Used Storage


Running Containers

System Load

I/O Usage


Container CPU usage

Container Memory usage 

Container Cached Memory usage

Container Network input

Container Network output

