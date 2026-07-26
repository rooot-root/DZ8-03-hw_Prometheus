Кошелев Дмитрий Владимирович

Задание 1.
скриншот
systemctl status prometheus.png
![alt text](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/systemctl%20status%20prometheus.png)


Задание 2.
systemctl status node-exporter.png
![alt text](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/systemctl%20status%20node-exporter.png

Задание 3.
Подключение Node Exporter к Prometheus

**Доступ к веб-интерфейсу:** `http://192.168.126.132:9090`

### Скриншот 1: Конфигурация (Status > Configuration)
Страница: `http://192.168.126.132:9090/config`

На скриншоте видно, что в конфигурации присутствует блок `scrape_configs` с двумя джобами: 
`prometheus` и `node_exporter`.

![Конфигурация Prometheus](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/prometheus_config.png)

### Скриншот 2: Цели (Status > Targets)
Страница: `http://192.168.126.132:9090/targets`

На скриншоте видно, что оба эндпоинта имеют статус **UP**:
- `http://localhost:9090` - Prometheus
- `http://localhost:9100` - Node Exporter

![Цели Prometheus](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/prometheus_targets.png)

РЕШЕНИЕ:
![Задание 1](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/systemctl%20status%20prometheus.png)

![Задание 2](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/systemctl%20status%20node-exporter.png)

![Задание 3](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/prometheus_targets.png)
![Задание 3. Конфигурация Prometheus](https://github.com/rooot-root/DZ8-03-hw_Prometheus/blob/master/prometheus_config.png)





























