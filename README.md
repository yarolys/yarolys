<h1 align="center">Yaroslav Lysov</h1>

<p align="center">
  <b>Python Backend &amp; AI Engineer</b><br/>
  Строю бэкенды и LLM-агентов, которые живут в проде и приносят деньги бизнесу
</p>

<p align="center">
  <a href="https://t.me/KandyBobby">
    <img src="https://img.shields.io/badge/Telegram-написать-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" height="28" alt="Telegram" />
  </a>
</p>

---

### Чем занимаюсь

Бэкенд и AI-системы, которые работают в проде под нагрузкой и считаются деньгами, а не демками. Сейчас — **Camirix**: интеграционная платформа между CRM, маркетплейсами и складскими системами; на мне сервис интеграций — очереди, идемпотентная доставка, OAuth-провайдеры, автономные Telegram-агенты.

**AI-модуль продаж.** Система сама ведёт переписку с клиентом в WhatsApp, Avito, Telegram и VK, считает предварительную стоимость и двигает сделку по воронке Bitrix24.

- **штат менеджеров с 20 до 5 человек** — экономия ФОТ до 5 млн ₽ в год
- **первый ответ клиенту за 2 минуты** в любое время суток, включая ночь и выходные
- LLM не пишет клиенту напрямую: модель возвращает строгий контракт `{reply, action}`, исполняет детерминированный код после валидации. Цену считает отдельный модуль по прайсу — нейросеть не влияет на финансовые расчёты, а откатить сделку назад не может на уровне кода
- три агента с промптами в БД (продажи, первый контакт, HR-скрининг), детерминированная маршрутизация по стадии сделки, RAG на Qdrant с MMR-выборкой

**Внутренняя платформа автоматизации операций.** Обработка тикетов, коммуникация с партнёрами через Telegram, real-time мониторинг источников.

- **70% кейсов закрываются без оператора**, среднее время обработки — с 2 часов до 15 минут
- **300 Telegram-аккаунтов** в пуле с автоматической ротацией, до 10 000 сообщений в сутки
- **>5000 каналов** под мониторингом с AI-классификацией, 50 000 сообщений в сутки
- нагрузка на ручную поддержку ниже на 60%, локализация инцидента — с часов до 10–15 минут

**Стриминговая платформа.** Высоконагруженный бэкенд с нуля: видео-контент, загрузка через S3, схема на 30+ таблиц и 60+ связей со строгой транзакционной моделью. Стабильность выросла на 40%, time-to-market фич — на 25%. Команда: 5 бэкенд, 2 фронтенд, DevOps, QA, продакт.

**Высоконагруженные Telegram-боты.** Telethon и aiogram, асинхронные запросы, фоновые задачи на Celery + Redis, классификация обращений через LLM, микросервисная архитектура, CI/CD и Sentry. Бот-помощник онлайн-курса держал **10k+ пользователей**.

---

### Стек

**Backend** &nbsp;Python 3.12 · FastAPI · SQLAlchemy 2.0 (async) · Alembic · Pydantic · AIOHTTP
**Данные** &nbsp;PostgreSQL · Redis · Qdrant · S3
**Очереди и задачи** &nbsp;Celery · RabbitMQ · Apache Kafka · APScheduler
**AI** &nbsp;OpenAI API · Claude · LangChain · LangGraph · faster-whisper
**Telegram** &nbsp;aiogram (Bot API) · Telethon (MTProto, userbot)
**Frontend** &nbsp;React · TypeScript · Vite · Tailwind CSS
**Инфра** &nbsp;Docker · Nginx · GitHub Actions · Prometheus · Grafana · Sentry

---

### Проекты

| | |
|---|---|
| **[AIgent](https://github.com/yarolys/AIgent)** | Автономный AI-агент на LangChain: планирование задач, вызов инструментов, работа с памятью |
| **[Roomly](https://github.com/yarolys/Roomly-FastAPI)** | Система бронирования отелей на FastAPI — поиск номеров, брони, аутентификация |
| **[ExampleTelegramBot](https://github.com/yarolys/ExampleTelegramBot)** | Готовый шаблон для быстрого старта Telegram-ботов на aiogram |

---

<p align="center">
  <img src="github-snake.svg" alt="contribution graph" width="800"/>
</p>
