<br clear="both">

<div align="center">
  <img height="300" width="600" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif"  />
</div>

###

<h1 align="center">Hi👋 I`m Yaroslav Lysov!</h1>

###

<div align="center">
  <a href="https://t.me/KandyBobby" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="telegram logo"  />
  </a>
</div>

###

<h3 align="left">👩‍💻  About me</h3>

###

<p align="left">Python backend & AI engineer. Я строю системы, которые работают в продакшене под нагрузкой и измеряются деньгами, а не демками: интеграционные платформы, LLM-агенты, высоконагруженные сервисы обработки сообщений.

<b>AI-модуль продаж.</b> Система сама ведёт переписку с клиентом в WhatsApp, Avito, Telegram и VK, считает предварительную стоимость и двигает сделку по воронке Bitrix24. Результат — штат менеджеров сократился с 20 до 5 человек (экономия ФОТ до 5 млн ₽ в год), а время первого ответа стабилизировалось на 2 минутах в любое время суток. Ключевое архитектурное решение: LLM не пишет клиенту напрямую — модель возвращает строгий контракт {reply, action}, а исполняет детерминированный код после валидации. Цену считает отдельный модуль по прайсу, поэтому нейросеть не влияет на финансовые расчёты; откатить сделку назад система не может на уровне кода. Три агента с промптами в БД, детерминированная маршрутизация по стадии сделки, RAG на Qdrant с MMR-выборкой.

<b>Платформа автоматизации операций.</b> Обработка тикетов, коммуникация с партнёрами через Telegram, real-time мониторинг источников. 70% кейсов закрываются без оператора, среднее время обработки упало с 2 часов до 15 минут. Система массовой коммуникации: 300 Telegram-аккаунтов в пуле с автоматической ротацией и rate limiting, до 10 000 сообщений в сутки. Мониторинг >5000 каналов с AI-классификацией — 50 000 сообщений в сутки. Нагрузка на ручную поддержку ниже на 60%, локализация инцидентов — с часов до 10–15 минут.

<b>Стриминговая платформа.</b> Высоконагруженный бэкенд с нуля: видео-контент, загрузка через S3, схема на 30+ таблиц и 60+ связей со строгой транзакционной моделью. Стабильность выросла на 40%, time-to-market новых фич — на 25%.

<b>Высоконагруженные Telegram-боты.</b> Telethon и aiogram, фоновые задачи на Celery + Redis, классификация обращений через LLM, микросервисная архитектура, CI/CD и Sentry. Бот-помощник онлайн-курса устойчиво держал 10k+ пользователей.</p>


<p align="center">
 <img width="600" src="github-snake.svg" alt="snake"/>
</p>

###

<h3 align="left">🛠 My stack:</h3>

###

<p align="left">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/fastapi-colored.svg" width="36" height="36" alt="Fast API" /></a><a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a><a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" /></a><a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tailwindcss-colored.svg" width="36" height="36" alt="TailwindCSS" /></a><a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" /></a><a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" /></a><a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" /></a><a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode.svg" width="36" height="36" alt="VS Code" /></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" height="25" alt="Redis" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" height="25" alt="Nginx" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" height="25" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" height="25" alt="Grafana" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" height="25" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Alembic-6BA81E?style=for-the-badge&logo=alembic&logoColor=white" height="25" alt="Alembic" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" height="25" alt="Celery" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" height="25" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" height="25" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" height="25" alt="Prometheus" />
  <img src="https://img.shields.io/badge/aiogram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" height="25" alt="aiogram" />
  <img src="https://img.shields.io/badge/Telethon-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" height="25" alt="Telethon" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" height="25" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" height="25" alt="LangGraph" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" height="25" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white" height="25" alt="Claude AI" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" height="25" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=airtable&logoColor=white" height="25" alt="Airtable" />
  <img src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white" height="25" alt="Sentry" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" height="25" alt="Pytest" />
</p>
                    
###

<h3 align="left">🔥   GitHub stats :</h3>


###

<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=yarolys&theme=discord_old_blurple" height="150" alt="stats graph"  />
  <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=yarolys&theme=prussian" height="150" alt="streak stats" /></a>
</div>

###
