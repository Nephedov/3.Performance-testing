# "Проведение нагрузочного тестирования WEB"

## Решения
#### Задание 1
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Blazemeter/RECORD-08-16-23-8-41-25-PM.jmx">Скрипт</a> тестового сценария BlazeMeter с нагрузкой.
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Blazemeter/RECORD-08-16-23-8-41-25-PM.png">Скриншот</a> с результатами нагрузки.

  
#### Задание 2
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/Nephedov-test.jmx">Nephedov-test.jmx</a> - профиль нагрузки с тестовым сценарием Jmeter.
* Скриншот <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/SummaryReport.jpg">SummaryReport.jpg</a> результатов выполнения профиля нагрузки.
* Скриншот <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/ViewResultTree.jpg">ViewResultTree.jpg</a> результатов выполнения профиля нагрузки.

#### Задание 3
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/JMeter/Nephedov-test.jmx">Nephedov-test.jmx</a> - профиль нагрузки с тестовым сценарием Jmeter, с добавлением сбора
  метрик.
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/InfluxDB/Dashboards/apache_jmeter.yml">apache_jmeter.yml</a> - конфигурация сбора метрик Jmeter для InfluxDB.
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Grafana/Dashboards/JMeter%20Performance%20Testing%20Dashboard-Nephedov93.json">JMeter Performance Testing Dashboard-Nephedov93.json</a> - дашборд
  Grafana для отображения метрик из InfluxDB.
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Screenshots/InfluxDbJMeterMetrics.png">InfluxDbJMeterMetrics.png</a> - скриншот дашборда InflixDB по результатам выполнения
  профиля нагрузки.
* <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Screenshots/GrafanaJmeterMetrics.png">GrafanaJmeterMetrics.png</a> - скриншот дашборда Grafana по результатам выполнения
  профиля нагрузки.
  
## Что было сделано
#### Задание 1
* Зарегистрирован и установлен плагин [BlazeMeter](https://chromewebstore.google.com/detail/mbopgmdnpcbohhpnfglgohlbhfongabi?hl=ru&utm_source=ext_sidebar) для Google Chrome.
* Записан и проигран скрипт <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Blazemeter/RECORD-08-16-23-8-41-25-PM.jmx">тестового сценария</a> с помощью системы BlazeMeter.
* Зафиксированы результаты получившейся нагрузки - <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Blazemeter/RECORD-08-16-23-8-41-25-PM.png">Скриншот</a>.


#### Задание 2
* Склонирован репозиторий с [тестовым сайтом кинотеатра](https://github.com/mshegolev/congenial-potato/) и поднят
  <a href="https://github.com/mshegolev/congenial-potato/blob/main/cinema/docker-compose.yml">docker-compose.yml</a> с MariaDB и остальными конфигурациями для работы сайта.
* Настроен профиль нагрузки и реализован тестовый сценарий по открытию сайта и получения QR-кода в Jmeter -
  <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/Nephedov-test.jmx">Nephedov-test.jmx</a>.
* Зафиксирован отчет Summary, результата прохождения тестового профиля - Скриншот
  <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/SummaryReport.jpg">SummaryReport.jpg</a>.
* Зафиксирован отчет ViewResultTree, результата прохождения тестового профиля - Скриншот
  <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Jmeter/ViewResultTree.jpg">ViewResultTree.jpg</a>.

 #### Задание 3
* Добавлена запись метрик к профилю нагрузки - <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/JMeter/Nephedov-test.jmx">Nephedov-test.jmx</a>.
* Сконфигурирован <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/InfluxDB/Dashboards/apache_jmeter.yml">apache_jmeter.yml</a> для отправки Jmeter метрик в InfluxDB.
* Скофигурирован
 <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Grafana/Dashboards/JMeter%20Performance%20Testing%20Dashboard-Nephedov93.json">JMeter Performance Testing Dashboard-Nephedov93.json</a> - JSON
дашборда Grafana, для отображения метрик из InfluxDB.
* Зафиксировано отображение метрик InfluxDB по результатам выполнения профиля нагрузки -
  <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Screenshots/InfluxDbJMeterMetrics.png">InfluxDbJMeterMetrics.png</a>.
* Зафиксировано отображение метрик Grafana по результатам выполнения профиля нагрузки -
  <a href="https://github.com/Nephedov/Performance-test_Load-web/blob/main/Additional%20task/Screenshots/GrafanaJmeterMetrics.png">GrafanaJmeterMetrics.png</a>.

  

## Предусловие задания:
* Провести раунд тестирования добавления комментария
* Необходимо самостоятельно написать сценарий тестирования покупки билета и получение QR кода.
* Сохранить результаты тестирования

Провести раунд тестирования добавления комментария.

Сценарий:
1. Открыть блог [http://cw24054-wordpress-zu0z0.tw1.ru/](http://cw24054-wordpress-zu0z0.tw1.ru/)
2. Перейти на страницу добавления комментария [Привет, Мир!](https://cw24054-wordpress-zu0z0.tw1.ru/2022/12/11/привет-мир/)
2. Добавить комментарий, заполнив поле Comment

### Описание Задания 1. Работа с `blazemeter`:
- зарегистрироваться на сайте [blazemeter](https://www.blazemeter.com/)
- установить плагин [blazemeter](https://chromewebstore.google.com/detail/mbopgmdnpcbohhpnfglgohlbhfongabi?hl=ru&utm_source=ext_sidebar)
- записать тест добавления комментария с помощью системы `blazemeter`
- проиграть скрипт добавления комментария в системе `blazemeter`
- прислать скриншоты получившейся нагрузки

### Описание Задания 2.  Работа с `jmeter`:
- Написать тест в Jmeter по открытию сайта http://localhost:8000/ и получению QR-кода билета
- Запустить тест для 1 пользователя
- Сделать скриншот о выполнении сценария с помощью `View Results Tree`
- Сделать скриншот стандартного отчета jmeter о проведенном тестировании
    ```bash
    jmeter -n -t <test JMX file> -l <test log file> -e -o <Path to output folder>

### Описание Задания 3.  Работа с `jmeter` (задание со звездочкой):   
- Настроить запись метрик в систему мониторинга (любой стэк).
- Запустить тест в соответствии с разработанным профилем нагрузки.
- Сделать скриншот полученных результатов из системы монитронига.
