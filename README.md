## 🚀 Проекты

### 📌 [Kidkod.ru — сайт образовательного центра](https://kidkod.ru)
**Роль:** Fullstack-разработчик  
**Стек:** Django, Wagtail CMS, Celery + Redis, HTML/CSS/JS, API-интеграции (Moyklass, tg)

Разработал и внедрил полноценный сайт образовательного центра с возможностью редактирования контента через Wagtail CMS.  
Интеграция с API Moyklass для управления обучением, реализация задач по расписанию через Celery.  
Интеграция с API tg для управления рассылками.
Оптимизация загрузки и SEO-структуры для поисковых систем.

---

### 📌 [keitaro-обертка](https://github.com/raferalston/keitaro-wrapper)

**Роль:** Backend-разработчик  
**Стек:** Django, Vue, Docker

Сервис для добавления рекламных кампаний для Facebook

--- 

### 📌 [Банковские платежи](https://github.com/raferalston/bank-payments)

**Роль:** Backend-разработчик  

**Стек:** FastAPI, Tortoise ORM, PostgreSQL, Redis, Celery, Flower, Aerich, httpx, Pydantic, Docker

REST API для работы с платежами по заказам. Поддержка наличных и эквайринга: создание платежей (депозит), возвраты, синхронизация статусов с банковским API. Заказы со статусами оплаты (не оплачен / частично / оплачен), валидация сумм и типов платежей. Фоновое подтверждение эквайринга через Celery, миграции Aerich, тесты на pytest.

---

### 📌 [Task Control API - Асинхронное управление задачами](https://github.com/raferalston/tasks-app)
Роль: Backend-разработчик
Стек: Django, DRF, Celery, Redis, PostgreSQL, Docker, JWT, drf-spectacular

REST API для управления асинхронными задачами с использованием Django REST Framework, Celery и Redis. Пользователи могут создавать задачи (сложение чисел и обратный отсчёт), отслеживать статус выполнения и фильтровать задачи по состоянию.

---

### 📌 [Complaint Workflow System — система автоматизации обработки жалоб](https://github.com/raferalston/complaint_service)
Роль: Backend-разработчик
Стек: FastAPI, SQLite (aiosqlite), httpx, n8n, Telegram Bot API, Google Sheets API

Разработал backend-сервис для обработки пользовательских жалоб с автоматической категоризацией и анализом тональности через внешние API.
Создал mock-сервисы для локального тестирования без реальных API.
Настроил автоматизацию процессов в n8n: сбор жалоб, уведомления в Telegram, запись в Google Sheets и автоматическое обновление статуса жалобы.
Проект включает готовые скрипты для локального тестирования и демонстрации функциональности.

---

### 📌 [Тестовое задание — image moderation](https://github.com/raferalston/image_moderation_api)
**Роль:** Использование FastAPI + Sightengine для проверки изображений  
**Стек:** Python, FastAPI

Это минималистичное FastAPI-приложение для проверки изображений на наличие NSFW-контента (обнажённость, оружие, наркотики, насилие и другие категории) с использованием API сервиса Sightengine.

---

### 📌 [Тестовое задание — Scrapy парсер](https://github.com/raferalston/scrapy_parser_task)
**Роль:** Использование фреймворка Scrapy для получения данных о товарах  
**Стек:** Python, scrapy

Парсиннг и валидация данных полученных с помощью scrapy.

---

### 📌 [Тестовое задание — CSV read and aggregate data](https://github.com/raferalston/csv_reader)
**Роль:** Python скрипт обработки csv файла и аггрегации данных внутри  
**Стек:** Python (без pandas)

Аггрегация данных из табличных данных с возможность добавления новых методов.

---

### 📌 [Тестовое задание — REST API](https://github.com/raferalston/rest-api-task-tradepoints)
**Роль:** Backend-разработчик  
**Стек:** Django, Django REST Framework

Создание REST API с фильтрацией и поиском по геолокации торговых точек.  
Фокус на архитектуре, читаемости кода и правильной обработке запросов.  
Использование сериализаторов и кастомных фильтров в DRF.

---

### 📌 [Mortgage REST API — ипотечный калькулятор](https://github.com/raferalston/mortgage-rest-api-example)
**Роль:** Backend-разработчик  
**Стек:** Django, DRF, Docker

Сервис расчёта ипотечных предложений с возможностью фильтрации банков по заданным параметрам.  
Проект развёрнут в Docker-контейнере и готов к продакшену.  
Пример структурированной бизнес-логики с API-интерфейсом.

---

### 📌 [Message App — отложенная отправка сообщений](https://github.com/raferalston/message-app)
**Роль:** Backend-разработчик  
**Стек:** Django, DRF, Celery, Redis, Docker

API-сервис для создания, хранения и отложенной отправки сообщений.  
Реализована очередь задач через Celery + Redis, развёртывание в Docker.  
Проект демонстрирует event-based архитектуру и работу с фоновыми задачами.

---

### 📌 [Telegram-бот для преподавателей с интеграцией CRM](https://github.com/raferalston/crm-tg-heroku-bot)
**Роль:** Разработчик бота  
**Стек:** Python, Telegram Bot API, Heroku

Telegram-бот с авторизацией, расписанием занятий и интеграцией с внешним CRM.  
Развёрнут на Heroku, использует webhook и поддерживает интерактивные команды.  
Ускоряет повседневные задачи преподавателя, минимизируя работу с CRM вручную.
