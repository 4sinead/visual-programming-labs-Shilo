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

## Скриншоты

### Часть 1. Версия Node-RED и Node.js
![Версия](../screenshots/1version.png)

### Часть 2.1 — Inject → Debug
![Inject Debug](../screenshots/1injectDebug.png)

### Часть 2.2 — Function node
![Function](../screenshots/2function.png)

### Часть 2.3 — Switch node
![Switch](../screenshots/3switch.png)

### Часть 2.4 — Change node
![Change](../screenshots/4change.png)

### Часть 2.5 — Template node
![Template](../screenshots/4template.png)

### Часть 2.6 — HTTP Request
![HTTP Request](../screenshots/6httpRequest.png)

### Часть 2.7 — MQTT
![MQTT](../screenshots/7mttq.png)

### Часть 2.8 — GET-эндпоинты

**Успешный запрос `/api/text`:**
![Text](../screenshots/8text.png)

**Успешный запрос `/api/info`:**
![Info](../screenshots/8info.png)

**Успешный запрос `/api/items/5`:**
![Items OK](../screenshots/8items.png)

**Ошибка 400 (`/api/items/abc`):**
![Error 400](../screenshots/8idError.png)

**Ошибка 404 (`/api/items/500`):**
![Not Found](../screenshots/8notFound.png)

### Часть 2.9 — Dashboard
![Dashboard](../screenshots/9ui.png)

### Часть 2.10 — Telegram-бот
![Telegram](../screenshots/10tg.png)

### Часть 2.11 — Файлы
![Files](../screenshots/11file.png)

### Часть 2.12 — Контекст
![Context](../screenshots/12counter.png)

### Ачивка 10 — SQLite

**Работа с SQLite (создание таблиц, вставка, выборка):**
![SQLite](../screenshots/sqlite.png)

**Сохранение после перезапуска Node-RED:**
![SQLite Reload](../screenshots/sqliteReload.png)

Вывод: Во время выполнения я освоил основные ноды в node-red, их связь, понял в каких сферах 
это применимо. Node-red способен облегчить жизнь тем, кто не хочет разбираться в синтаксисе js, 
но при этом хочет например создать тг-бота. Также я познакомился с SQLite расширением? для 
node-red, которое вместе с нодами для тг дают много возможностей для реализации своих проектов.
