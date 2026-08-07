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

Сейчас — **Camirix**: интеграционная платформа, связывающая CRM (amoCRM, Bitrix24), маркетплейсы и складские системы. Отвечаю за сервис интеграций: очереди, идемпотентная доставка, OAuth-провайдеры, автономные Telegram-агенты.

До этого спроектировал и вывел в прод AI-модуль продаж, который сам ведёт переписку с клиентом, считает предварительную стоимость и двигает сделку по воронке:

- **штат менеджеров сокращён с 20 до 5** — экономия ФОТ до 5 млн ₽/год
- **время первого ответа клиенту — 2 минуты** в любое время суток, включая ночь и выходные
- LLM никогда не пишет напрямую в клиентский канал: модель возвращает строгий JSON-контракт `{reply, action}`, всё исполнение — детерминированный код с валидацией

---

### Стек

**Backend** &nbsp;Python 3.12 · FastAPI · SQLAlchemy 2.0 · Alembic · Pydantic
**Данные** &nbsp;PostgreSQL · Redis · Qdrant
**Асинхронность** &nbsp;Celery · RabbitMQ · APScheduler
**AI** &nbsp;OpenAI API · Claude · LangChain · LangGraph
**Инфра** &nbsp;Docker · Nginx · GitHub Actions · Prometheus · Grafana

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
