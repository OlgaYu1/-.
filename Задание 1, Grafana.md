# Grafana
> ***Примечание:*** определения для специальных терминов и наименований, используемых ниже по тексту, содержатся в файле "термины и определения к Заданию 1", переход возможен кликом по ссылке.

**Grafana** - это инструмент с открытым исходным кодом для визуализации, мониторинга и анализа данных, собранных из разных источников. 
Используется для представления в графическом виде [временных рядов](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,%D0%92%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%80%D1%8F%D0%B4,-%D1%81%D0%BE%D0%B2%D0%BE%D0%BA%D1%83%D0%BF%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D1%82%D0%BE%D1%87%D0%B5%D0%BA%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) и текстовых данных, позволяет отслеживать поведение пользователей и производительность системы. 
Полученная информация поставляется конечному пользователю в виде визуальных отчетов - диаграмм, графиков, таблиц, предупреждений:

<img width="750" alt="пример Grafana1" src="https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/assets/154415031/e0e24664-77c5-4cee-92e6-c1b3fbeeaa90">

*Рис. 1. Пример визуала Grafana*

В  Grafana создаются [дашборды](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,%D0%94%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4,-%D0%BD%D0%B0%D0%B1%D0%BE%D1%80%20%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D1%85%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9) с [панелями](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/blob/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%81%20%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-,%D0%9F%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C,-First%20Header), каждая из которых отображает определенные показатели в течение установленного периода времени. 
Дашборды состоят из наборов панелей, они универсальны; и панели, и дашборды можно настраивать для конкретного проекта или с учетом любых потребностей разработки/бизнеса.

В качестве примера встроенных панелей Grafana можно привести:
— Graph — панель с графиками,
— Stat (ранее SingleStat) — панель с одиночным графиком и возможностью отображения моментального значения метрики,
— Gauge — панель в формате спидометра,
— Bar Gauge — панель с возможностью отображения нескольких метрик на вертикальной гистограмме,
— Table — панель с представлением в виде таблицы,
— Text — панель для отображения произвольного текста (подписи),
— Heatmap — панель для отображения тепловой карты значений метрик,
— Alert list — панель для отображения событий из внешних систем,
— Dashboard list — комбинированная панель для отображения дашбордов, добавленных в избранное,
— News — панель для отображения новостной ленты из внешних источников,
— Zabbix problems — панель для отображения событий из системы мониторинга Zabbix,
— Logs — панель для отображения строчек лога, которые собираются одной из внешних систем.

....

Использование Grafana возможно как локально на операционных системах (Linux - Debian, Ubuntu, CentOS, Fedora, OpenSuse, RedHat; Mac и Windows.), так и на контейнерных платформах, в нашем случае - [Kubernetes](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,Kubernetes,-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%BE%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5), где Grafana используется для визуализации данных, собранных с помощью [Prometheus](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D0%B0%D1%8F%20%D0%B4%D0%BB%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-,Prometheus,-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%BE%D0%B2%20%D0%B8). 
Связка Grafana + Prometheus позволяет следить за использованием памяти, процессора и хранилища кластеров Kubernetes. 
Prometheus используется для сбора и хранения данных метрик из клиентских приложений, а затем эти данные доступны для анализа и визуализации с помощью Grafana.
Мониторинг кластера посредством Grafana и Prometheus сообщает о потенциальных узких местах производительности, работоспособности кластера и показателях производительности, при одновременной возможности визуализации использования сети, создания шаблонов использования ресурсов модулей и общего обзора того, что происходит в вашем кластере.

Grafana также поддерживает интеграцию с разными источниками данных, кроме Prometheus это могут быть, напр., [Alertmanager](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-,Alertmanager,-Kubernetes), [Azure Monitor](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Alertmanager-,Azure%20Monitor,-Kubernetes), [Google Cloud Monitoring](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Google%20Cloud%20Monitoring), [Graphite](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Google%20Cloud%20Monitoring-,Graphite,-Kubernetes), [Jaeger](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Graphite-,Jaeger,-Kubernetes), [Loki](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Jaeger-,Loki,-Kubernetes), [MySQL](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=Loki-,MySQL,-%7C%20Prometheus%20%7C%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%BE%D0%B2), [VictoriaMetrics](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20IT%2D%D0%BE%D0%B1%D0%BE%D1%80%D1%83%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-,VictoriaMetrics,-%D0%92%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D1%80%D1%8F%D0%B4), [VictoriaMetrics cluster](https://github.com/OlgaYu1/Test-task-SberTech-Olga-Yuvchenko/edit/main/%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%20%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8E%201.md#:~:text=VictoriaMetrics%20cluster) и многие другие готовые решения; кроме того возможно создание кастомных плагинов и сервисов, отвечающих на конкретные запросы разработки. Однако сновным хранилищем данных для Grafana выступает именно Prometheus ввиду его фокусировки на предоставлении аналитической информации и предупреждений в режиме реального времени для контейнерных сред и сред на основе микросервисов; основной вариант использования Prometheus — мониторинг инфраструктуры и приложений с упором на надежность и масштабируемость.

## *Основные функции Grafana в Kubernetes:*
- *Уведомления* - отправка оповещений через различные каналы уведомлений, включая PagerDuty, SMS, email, VictorOps, OpsGenie или Slack;
- *Аннотации* - возможность маркировки графиков разнообразными событиями из разных источников данных;
- *Аутентификация* - поддержка различных методов аутентификации, таких как LDAP и OAuth, и возможность сопоставления пользователей с организациями и командами;
- *Обеспечение* - автоматизация настройки с помощью сценариев;
- *Разрешения* - возможность создания команд пользователей и управления доступом к папкам и информационным панелям;
- *Исследование* - изучение метрик, журналов и трассировок с помощью специальных запросов и динамической детализации;
- *Шаблоны* - создание информационных панелей, которые можно повторно использовать для множества различных случаев использования, внося необходимые изменения;
- *Настройка* - возможность внесения изменений в конфигурацию и переменные среды - настройка портов по умолчанию, уровней ведения журнала, IP-адреса электронной почты, безопасности и др.;
- *Импорт* - заимствование информационных панелей и плагинов из постоянно пополняемой официальной библиотеки;

## *Пример использования*
В качестве примеров приведем установку, удаление, ///// Grafana в Kubernetes.




