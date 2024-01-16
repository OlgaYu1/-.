# Grafana
> ***Примечание:*** определения для специальных терминов, используемых ниже по тексту, содержатся в файле "термины и определения к Заданию 1", переход возможен кликом по ссылке.

**Grafana** - это инструмент с открытым исходным кодом для визуализации, мониторинга и анализа данных, собранных из разных источников. 
Используется для представления в графическом виде [временных рядов](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,%D0%92%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%80%D1%8F%D0%B4,-%D1%81%D0%BE%D0%B2%D0%BE%D0%BA%D1%83%D0%BF%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D1%82%D0%BE%D1%87%D0%B5%D0%BA%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) и текстовых данных, позволяет отслеживать поведение пользователей и производительность системы. 
Полученная информация поставляется конечному пользователю в виде визуальных отчетов - диаграмм, графиков, таблиц, предупреждений:

<img width="750" alt="пример Grafana1" src="https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/assets/154415031/e0e24664-77c5-4cee-92e6-c1b3fbeeaa90">

*Рис. 1. Пример визуала Grafana*

В  Grafana создаются [дашборды](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,%D0%94%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4,-%D0%BD%D0%B0%D0%B1%D0%BE%D1%80%20%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D1%85%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9) с [панелями](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%9F%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C,-First%20Header), каждая из которых отображает определенные показатели в течение установленного периода времени. 
Дашборды состоят из наборов панелей, они универсальны; и панели, и дашборды можно настраивать для конкретного проекта или с учетом любых потребностей разработки/бизнеса.

В качестве примера встроенных панелей Grafana можно привести:
- Graph - панель с графиками;
- Stat - панель с одиночным графиком и возможностью отображения моментального значения [метрики](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B0,-%D0%9F%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C);
- Gauge - панель в формате спидометра;
- Bar Gauge - панель с возможностью отображения нескольких метрик на вертикальной [гистограмме](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%B2%D0%B0%D0%BB-,%D0%93%D0%B8%D1%81%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0,-%D0%94%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4);
- Table - панель с представлением в виде таблицы;
- Text - панель для отображения произвольного текста (подписи);
- Heatmap - панель для отображения тепловой карты значений метрик;
- Alert list - панель для отображения событий из внешних систем;
- Dashboard list - комбинированная панель для отображения дашбордов, добавленных в избранное;
- News - панель для отображения новостной ленты из внешних источников;
- Logs - панель для отображения строчек [лога](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%9B%D0%BE%D0%B3,-%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B0), которые собираются одной из внешних систем.

Помимо использования встроенных панелей, существует возможность установки дополнительных (напр., из официального сообщества grafana.com), а также создания собственных панелей.

Grafana используется как локально на операционных системах (Linux - Debian, Ubuntu, CentOS, Fedora, OpenSuse, RedHat; Mac и Windows.), так и на контейнерных платформах, в нашем случае - [Kubernetes](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,Kubernetes,-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%BE%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5), где Grafana используется для визуализации данных, собранных с помощью [Prometheus](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D0%B0%D1%8F%20%D0%B4%D0%BB%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-,Prometheus,-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%BE%D0%B2%20%D0%B8). 
Связка Grafana + Prometheus позволяет следить за использованием памяти, процессора и хранилища [кластеров](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%9A%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80,-%D0%9B%D0%BE%D0%B3) Kubernetes. 
Prometheus используется для сбора и хранения данных метрик из клиентских приложений, а затем эти данные доступны для анализа и визуализации с помощью Grafana.
Мониторинг кластера посредством Grafana и Prometheus сообщает о потенциальных узких местах производительности, работоспособности кластера и показателях производительности, при одновременной возможности визуализации использования сети, создания шаблонов использования ресурсов модулей и общего обзора того, что происходит в вашем кластере.

Grafana также поддерживает интеграцию с разными источниками данных, кроме Prometheus это могут быть, напр., [Alertmanager](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,Alertmanager,-Kubernetes), [Azure Monitor](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Alertmanager-,Azure%20Monitor,-Kubernetes), [Google Cloud Monitoring](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Google%20Cloud%20Monitoring), [Graphite](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Google%20Cloud%20Monitoring-,Graphite,-Kubernetes), [Jaeger](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Graphite-,Jaeger,-Kubernetes), [Loki](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Jaeger-,Loki,-Kubernetes), [MySQL](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Loki-,MySQL,-%7C%20Prometheus%20%7C%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%BE%D0%B2), [VictoriaMetrics](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,VictoriaMetrics,-%D0%92%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%80%D1%8F%D0%B4), [VictoriaMetrics cluster](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=VictoriaMetrics%20cluster) и многие другие готовые решения; кроме того возможно создание кастомных плагинов и сервисов, отвечающих на конкретные запросы разработки. 
Однако сновным хранилищем данных для Grafana выступает именно Prometheus ввиду его фокусировки на предоставлении аналитической информации и предупреждений в режиме реального времени для контейнерных сред и сред на основе микросервисов, мониторинга инфраструктуры и приложений с упором на надежность и масштабируемость.

![пример дашборда Prometheus](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/assets/154415031/e88a38be-fb93-4972-b4e1-bcd80feff4e3)

*Рис. 2. Пример мониторинга кластера Kubernetes с помощью Prometheus* 

Итак, **основной функцией Grafana в Kubernetes** является графическое представление данных, в рамках реализации данной функции используются следующие средства:  
- *Уведомления* - отправка оповещений через различные каналы уведомлений, включая [PagerDuty](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=MySQL-,PagerDuty,-Prometheus), SMS, email, [VictorOps](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=VictoriaMetrics%20cluster-,VictorOps,-%D0%92%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%80%D1%8F%D0%B4), [OpsGenie](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=MySQL-,OpsGenie,-PagerDuty) или [Slack](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,Slack,-VictoriaMetrics);
- *Аннотации* - возможность маркировки графиков разнообразными событиями из разных источников данных;
- *Аутентификация* - поддержка различных методов аутентификации, таких как [LDAP](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D0%B0%D1%8F%20%D0%B4%D0%BB%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-,LDAP,-Loki) и [OAuth](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=MySQL-,OAuth,-OpsGenie), и возможность сопоставления пользователей с организациями и командами;
- [*Снимок*](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D1%8F%D1%82%D1%8C%20%D0%B8%D1%85%20%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%80-,%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA,-Editing%20Test%2Dtask) Kubernetes с представлением проблем , показывающий информацию о количестве кластеров, узлах, модулях и контейнерах, а также любые проблемы, требующие внимания;
- *Обеспечение* - автоматизация настройки с помощью сценариев, а также детализация данных с помощью единого интерфейса, возможность углубления в данные, переходя от узлов ([Nodes](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=MySQL-,Nod,-OAuth)) к модулям ([Pods](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=PagerDuty-,Pod,-Prometheus));
- *Разрешения* - возможность создания команд пользователей и управления доступом к папкам и панелям;
- *Исследование* - изучение метрик, [журналов](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%96%D1%83%D1%80%D0%BD%D0%B0%D0%BB,-%D1%84%D0%B0%D0%B9%D0%BB%20%D0%B8%D0%BB%D0%B8%20%D0%B1%D0%B0%D0%B7%D0%B0) и [трассировок](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-,%D0%A2%D1%80%D0%B0%D1%81%D1%81%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0,-%D0%BE%D1%82%D1%81%D0%BB%D0%B5%D0%B6%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2%20%D0%BF%D0%BE) с помощью специальных запросов и динамической детализации, включает в себя:
а. анализ исторических данных - возможность просмотра исторических данных за любой выбранный период времени,
б. прогноз ЦП и памяти - может помочь обеспечить доступность ресурсов во время пиков их использования, а также уменьшить количество неиспользуемых ресурсов из-за чрезмерного выделения ресурсов;
- *Эффективность* - представление, предназначенное для изучения и анализа использования ресурсов, повышения производительности и устранения проблем со стабильностью, сопоставляя среднее и максимальное использование ресурсов, а также наблюдения за использованием ресурсов для каждого кластера и [облачного провайдера](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B0-,%D0%9E%D0%B1%D0%BB%D0%B0%D1%87%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B2%D0%B0%D0%B9%D0%B4%D0%B5%D1%80,-%D0%9F%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C);
- *Шаблоны* - создание готовых дашбордов и панелей для анализа использования ресурсов и операций кластера, от уровня нескольких кластеров до отдельных контейнеров и модулей; которые можно повторно использовать для множества различных случаев, внося необходимые изменения;
- *Настройка* - возможность внесения изменений в конфигурацию и переменные среды - настройка портов по умолчанию, уровней ведения журнала, IP-адреса электронной почты, безопасности и др.;
- *Импорт* - заимствование информационных панелей и плагинов из постоянно пополняемой официальной библиотеки;
- Представление *затрат* для анализа стоимости ресурсов и управления затратами на инфраструктуру и выявления возможности потенциальной экономии;
- *Фильтры данных* - использование элементов управления с целью дополнительно указывать и сортировать данные, которые вы хотите просмотреть и проанализировать;
- *Цветовые подсказки* в качестве дополнительного средства обозначения статуса или состояния;
- Использование [*Recording Rules*](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,Recording%20Rules,-Slack) для увеличения скорости запросов дашбордов с панелями и оценки [alerting rules](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,Alerting%20rules,-Alertmanager).

## *Примеры сценариев использования Grafana в Kubernetes*
### Развертывание Grafana в Kubernetes
**Системные Требования** - минимальные требования к аппаратному и программному обеспечению.

***Минимальные требования*** к оборудованию:

- Дисковое пространство: 1 ГБ;
- Память: 750 МБ (около 750 МБ);
- ЦП: 250 м (около 2,5 ядер).

***Поддерживаемые базы данных.*** 
Grafana требуется база данных для хранения данных конфигурации, таких как пользователи, источники данных и информационные панели.

Grafana поддерживает следующие базы данных:
- SQLite 3;
- MySQL 5.7+;
- PostgreSQL 12+.

По умолчанию Grafana использует встроенную базу данных SQLite, которая хранится в папке установки Grafana, подходит для небольших сред.

***Поддерживаемые веб-браузеры:***

- Chrome/Chromium;
- Firefox;
- Safari;
- Microsoft Edge.

> ***Примечание:*** Включите порт `3000` в вашей сетевой среде, так как это порт Grafana по умолчанию.

**Развертывание Grafana в Kubernetes**

Рекомендуется создать новое [пространство имен](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D1%8F%D1%82%D1%8C%20%D0%B8%D1%85%20%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%80-,%D0%9F%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%BE%20%D0%B8%D0%BC%D0%B5%D0%BD,-%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA) в Kubernetes, чтобы лучше управлять, организовывать, распределять и управлять ресурсами кластера:

**1.** Чтобы создать пространство имен, выполните следующую команду:

```
kubectl create namespace my-grafana
```
*В этом примере пространство имен `my-grafana`.*

**2.** Чтобы проверить и просмотреть вновь созданное пространство имен, выполните следующую команду:

```
kubectl get namespace my-grafana
```

*Вывод команды предоставляет дополнительную информацию о вновь созданном пространстве имен.*

**3.** Создайте [файл манифеста YAML](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-,%D0%A4%D0%B0%D0%B9%D0%BB%20%D0%BC%D0%B0%D0%BD%D0%B8%D1%84%D0%B5%D1%81%D1%82%D0%B0%20YAML,-Editing%20Test%2Dtask) с именем `grafana.yaml`. Этот файл будет содержать необходимый код для развертывания:

```
touch grafana.yaml
```

*На следующем шаге вы определите следующие три объекта в файле YAML:*
| Объект | Описание |
| --- | --- |
| Постоянная заявка на объем (PVC) | Этот объект хранит данные. |
| Услуга | Этот объект обеспечивает сетевой доступ к Pod, определенному в развертывании. |
| Развертывание | Этот объект отвечает за создание модулей, обеспечение их актуальности и управление обновлениями [ReplicaSet](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Recording%20Rules-,ReplicaSet,-Slack) и [Rolling](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=ReplicaSet-,Rolling,-Slack). |

**4.** Скопируйте и вставьте следующее содержимое в файл `grafana.yaml`, сохраните его:

```
---
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: grafana-pvc
spec:
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 1Gi
---
apiVersion: apps/v1
kind: Deployment
metadata:
  labels:
    app: grafana
  name: grafana
spec:
  selector:
    matchLabels:
      app: grafana
  template:
    metadata:
      labels:
        app: grafana
    spec:
      securityContext:
        fsGroup: 472
        supplementalGroups:
          - 0
      containers:
        - name: grafana
          image: grafana/grafana:latest
          imagePullPolicy: IfNotPresent
          ports:
            - containerPort: 3000
              name: http-grafana
              protocol: TCP
          readinessProbe:
            failureThreshold: 3
            httpGet:
              path: /robots.txt
              port: 3000
              scheme: HTTP
            initialDelaySeconds: 10
            periodSeconds: 30
            successThreshold: 1
            timeoutSeconds: 2
          livenessProbe:
            failureThreshold: 3
            initialDelaySeconds: 30
            periodSeconds: 10
            successThreshold: 1
            tcpSocket:
              port: 3000
            timeoutSeconds: 1
          resources:
            requests:
              cpu: 250m
              memory: 750Mi
          volumeMounts:
            - mountPath: /var/lib/grafana
              name: grafana-pv
      volumes:
        - name: grafana-pv
          persistentVolumeClaim:
            claimName: grafana-pvc
---
apiVersion: v1
kind: Service
metadata:
  name: grafana
spec:
  ports:
    - port: 3000
      protocol: TCP
      targetPort: http-grafana
  selector:
    app: grafana
  sessionAffinity: None
  type: LoadBalancer
```

**5.** Выполните следующую команду, чтобы отправить манифест на сервер [API Kubernetes](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Alertmanager-,API%20Kubernetes,-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%2C%20%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D0%BE%D0%B5%20%D0%BF%D0%BE%D0%B7%D0%B2%D0%BE%D0%BB%D1%8F%D0%B5%D1%82):

```
kubectl apply -f grafana.yaml --namespace=my-grafana
```

*Эта команда создает объекты [PVC](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,PVC,-%D0%BF%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%B2%D0%B8%D1%80%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB), [Deployment](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Azure%20Monitor-,Deployment,-%22%D1%80%D0%B0%D0%B7%D0%B2%D0%B5%D1%80%D1%82%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%22%2C%20%D0%B0%D0%B1%D1%81%D1%82%D1%80%D0%B0%D0%BA%D1%86%D0%B8%D1%8F%20Kubernetes) и [Service](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Rolling-,Service,-%D0%B2%20Kubernetes%20%D1%8D%D1%82%D0%BE).*

**6.** Выполните следующие шаги, чтобы проверить состояние развертывания каждого объекта:

а. Для PVC выполните следующую команду:

```
kubectl get pvc --namespace=my-grafana -o wide
```

б. Для Deployment выполните следующую команду:
```
kubectl get deployments --namespace=my-grafana -o wide
```

в. Для Service выполните следующую команду:
```
kubectl get svc --namespace=my-grafana -o wide
```

### Установка и запуск Prometheus Node Exporter
Установите Node Exporter на все хосты, которые вы хотите отслеживать. Ниже покажем, как установить его локально.

Prometheus Node Exporter — широко используемый инструмент, предоставляющий системные метрики. 

**1.** После загрузки файла Prometheus Node Exporter извлеките его и запустите:

```
# NOTE: Replace the URL with one from the above mentioned "downloads" page.
# <VERSION>, <OS>, and <ARCH> are placeholders.
wget https://github.com/prometheus/node_exporter/releases/download/v<VERSION>/node_exporter-<VERSION>.<OS>-<ARCH>.tar.gz
tar xvfz node_exporter-*.*-amd64.tar.gz
cd node_exporter-*.*-amd64
./node_exporter
```

Вы должны увидеть такой вывод, указывающий, что Node Exporter теперь запущен и предоставляет метрики на порту 9100:

```
INFO[0000] Starting node_exporter (version=0.16.0, branch=HEAD, revision=d42bd70f4363dced6b77d8fc311ea57b63387e4f)  source="node_exporter.go:82"
INFO[0000] Build context (go=go1.9.6, user=root@a67a9bc13a69, date=20180515-15:53:28)  source="node_exporter.go:83"
INFO[0000] Enabled collectors:                           source="node_exporter.go:90"
INFO[0000]  - boottime                                   source="node_exporter.go:97"
...
INFO[0000] Listening on :9100                            source="node_exporter.go:111"
```

**2.** Убедитесь, что метрики экспортируются, сверив конечную точку `/metrics`:

```
curl http://localhost:9100/metrics
```

Вы должны увидеть такой вывод:

```
# HELP go_gc_duration_seconds A summary of the GC invocation durations.
# TYPE go_gc_duration_seconds summary
go_gc_duration_seconds{quantile="0"} 3.8996e-05
go_gc_duration_seconds{quantile="0.25"} 4.5926e-05
go_gc_duration_seconds{quantile="0.5"} 5.846e-05
# etc.
```

**3.** Для просмотра системных метрик, выполните следующую команду:

```
curl http://localhost:9100/metrics | grep "node_"
```

### Установка и настройка Prometheus 

**1.** После загрузки Prometheus извлеките его и перейдите в каталог, выполнив следующую команду:

```
tar xvfz prometheus-*.tar.gz
cd prometheus-*
```

**2.** Найдите в каталоге файл prometheus.yml.

**3.** Измените файл конфигурации Prometheus, чтобы отслеживать хосты, на которых вы установили Node Exporter, добавив следующий код:

```
 # A scrape configuration containing exactly one endpoint to scrape from node_exporter running on a host:
 scrape_configs:
     # The job name is added as a label `job=<job_name>` to any timeseries scraped from this config.
     - job_name: 'node'

     # metrics_path defaults to '/metrics'
     # scheme defaults to 'http'.

       static_configs:
       - targets: ['localhost:9100']
```

**4.** Для запуска службы Prometheus выполните следующую команду:

```
 ./prometheus --config.file=./prometheus.yml
```

**5.** Убедитесь, что Prometheus запущен, перейдя к `http://localhost:9090`.

Метрики Node Exporter были доставлены в Prometheus, далее они будут отправлены в Grafana.

### Настройка Prometheus для Grafana. Просмотр показателей Grafana с помощью Prometheus

**1.** Предоставление источника данных:

```
apiVersion: 1

datasources:
  - name: Prometheus
    type: prometheus
    access: proxy
    # Access mode - proxy (server in the UI) or direct (browser in the UI).
    url: http://localhost:9090
    jsonData:
      httpMethod: POST
      manageAlerts: true
      prometheusType: Prometheus
      prometheusVersion: 2.44.0
      cacheLevel: 'High'
      disableRecordingRules: false
      incrementalQueryOverlapWindow: 10m
      exemplarTraceIdDestinations:
        # Field with internal link pointing to data source in Grafana.
        # datasourceUid value can be anything, but it should be unique across all defined data source uids.
        - datasourceUid: my_jaeger_uid
          name: traceID

        # Field with external link.
        - name: traceID
          url: 'http://localhost:3000/explore?orgId=1&left=%5B%22now-1h%22,%22now%22,%22Jaeger%22,%7B%22query%22:%22$${__value.raw}%22%7D%5D'
```

**2.** Чтобы импортировать встроенную панель мониторинга, перейдите на страницу конфигурации источника данных.

**3.** Выберите вкладку «Панели мониторинга».

**4.** Среди отобразившихся информационных панелей для Grafana и Prometheus выберите необходимую и нажмите "импортировать", чтобы панель мониторинга импортировалась.

**5.** После импорта откройте установленную панель/дашборд.

![пример дашборда](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/assets/154415031/00ad6f4b-9d63-4f5e-800f-d48ff2e64576)

*Рис. 3. Пример импортированного дашборда*

**6.** Для установки дополнительных плагинов, напр., плагина для отображения круговых диаграмм - загрузите по ссылке https://grafana.com/grafana/plugins/grafana-piechart-panel и выполните следующую команду:

```
grafana-cli plugins install grafana-piechart-panel
```

**7.** Для завершения установки плагина перезапустите Grafana:

```
service grafana-server restart
```

![piechart-donut](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/assets/154415031/756d0d9c-0103-4982-8666-28f9d60cd255)

*Рис. 4. Пример установленного плагина круговых диаграмм*

Установленные панели доступны в разделе «Панели мониторинга» в главном меню Grafana и могут быть добавлены, как и любая другая основная панель в Grafana. 
Чтобы просмотреть список установленных панелей, нажмите пункт «Плагины» в главном меню - появятся как основные панели, так и установленные.
