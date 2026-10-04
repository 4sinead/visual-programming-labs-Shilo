Отчёт:
**Студент:** Шило Денис  
**Группа:** УИР-241
**Дата:** 04.10.2026
В ходе лабораторной работы я освоил Node-RED как low-code инструмент для 
визуального программирования. Собрал 12 потоков, охватывающих базовые и продвинутые ноды
Дополнительно выполнил ачивку №10 — работа с базой данных SQLite.
**Способ установки:** npm (глобальная установка).
node v24.21.0
Node-RED version: v5.0.7
Освоенные ноды:
- **Базовые:** inject, debug, function, switch, change, template.
- **Сетевые:** http request, http in, http response, mqtt in, mqtt out.
- **Dashboard:** ui_gauge, ui_chart.
- **Telegram:** telegram command, telegram sender.
- **Файлы:** file in (read file), file out (write file).
- **Контекст:** работа через `flow.get/set`, `global.get/set`.
- **SQLite:** sqlite, работа с базой данных.
AI-промпты использовал например при написании функций на js или при создании sql-запросов
Помоги составить SQL-запросы для создания двух таблиц (students и logs) и операций вставки/выборки
Напиши Function-нодус базовыми элементами JavaScript: let/const, if/else, цикл for, массив, объект
Скриншоты

### Поток 2.1. Inject → Debug
![01](screenshots/01-inject-debug.png)

### Поток 2.2. Function node
![02](screenshots/02-function.png)

### Поток 2.3. Switch node
![03](screenshots/03-switch.png)

### Поток 2.4. Change node
![04](screenshots/04-change.png)

### Поток 2.5. Template node
![05](screenshots/05-template.png)

### Поток 2.6. HTTP Request
![06](screenshots/06-http-request.png)

### Поток 2.7. MQTT
![07](screenshots/07-mqtt.png)

### Поток 2.8. GET-эндпоинты
![08a](screenshots/08a-text.png)
![08b](screenshots/08b-info.png)
![08c](screenshots/08c-items-ok.png)
![08d](screenshots/08d-items-400.png)
![08e](screenshots/08e-items-404.png)

### Поток 2.9. Dashboard
![09](screenshots/09-dashboard.png)

### Поток 2.10. Telegram-бот
![10](screenshots/10-telegram.png)

### Поток 2.11. Файлы
![11](screenshots/11-files.png)

### Поток 2.12. Контекст
![12](screenshots/12-context.png)

### Ачивка 10. SQLite
![ach10a](screenshots/ach10a-create-tables.png)
![ach10b](screenshots/ach10b-insert.png)
![ach10c](screenshots/ach10c-select.png)
![ach10d](screenshots/ach10d-after-restart.png)
![ach10e](screenshots/ach10e-flow.png)

Вывод: Во время выполнения я освоил основные ноды в node-red, их связь, понял в каких сферах 
это применимо. Node-red способен облегчить жизнь тем, кто не хочет разбираться в синтаксисе js, 
но при этом хочет например создать тг-бота. Также я познакомился с SQLite расширением? для 
node-red, которое вместе с нодами для тг дают много возможностей для реализации своих проектов.
