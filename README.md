# ⚡ CONSOLE // dim1oan_

```text
⚙️ STATUS: Active Backend Developer
🎓 LOCATION: MSTU "STANKIN" (Applied Informatics, 2029)
💬 TELEGRAM: @dim1oan | ✉️ EMAIL: 13dima112007@gmail.com
```

---

### 📡 Active Infrastructure (Мои Проекты)

Я разрабатываю децентрализованную экосистему для автоматизации и дистрибуции VPN-доступа. Код спроектирован под высокие нагрузки, полностью асинхронен и готов к продакшену.

#### ⚙️ [vpn-bot](https://github.com) — Ядро и Фоновые задачи
> Асинхронный Telegram-бот на aiogram 3.x для продажи VLESS+Reality доступа через API панели 3x-ui.
* **Woker Engine:** Изолированный планировщик `APScheduler` на 7 параллельных фоновых задач (динамический подсчет трафика, автоблокировки, биллинг).
* **Security:** Fernet-шифрование конфиденциальных данных в БД, вырезание секретов из JSON-логов (`structlog`).
* **Stack:** `Python 3.11+` • `Aiogram 3.x` • `SQLAlchemy 2.0` • `PostgreSQL` • `Pytest` • `Docker`

#### 🌐 [vpn-web-cabinet](https://github.com) — Веб-интерфейс (Кабинет)
> Высокопроизводительное веб-приложение на FastAPI, выступающее альтернативной точкой входа для клиентов без доступа к Telegram.
* **Shared DB Architecture:** Работает с той же базой данных, что и бот, в режиме `SQLite WAL` (Write-Ahead Logging) с защитой от дедлоков (`busy_timeout=5000`).
* **Web Security:** Авторизация через `bcrypt`, защита от межсайтовых запросов (`CSRF`) и строгий `Rate-Limiter` на уровне маршрутов.
* **Stack:** `FastAPI` • `Jinja2` • `Bootstrap 5` • `Pydantic v2` • `HTTPX ASGI Tests`

---

### 🧰 Core Core Tech Stack

```💼 Языки:      Python (Asyncio / ООП), SQL
🚀 Фреймворки:  FastAPI, Aiogram 3.x, SQLAlchemy, Pydantic, Alembic
🗄️ Базы данных: PostgreSQL, MySQL, SQLite (WAL)
🐳 Инфраструктура: Docker, Docker Compose, Nginx, Linux (Bash), Systemd, SFTP
🧪 Качество кода: Pytest, Ruff, Mypy
```

---

### 📊 GitHub Activity (Динамический График)

Этот неоновый график генерируется автоматически на основе моих реальных коммитов в репозитории:

<p align="left">
  <a href="https://github.com">
    <img src="https://vercel.app" alt="dim1oan activity graph" width="100%">
  </a>
</p>

---

### 🏆 Достижения и Статусы
*Все открытые ачивки (YOLO, Pull Shark, Pair Extraordinaire) и плашки контрибьютора GitHub автоматически выводятся в **левой панели** моего профиля прямо под аватаркой!*

```text
🚀 Готов к стажировкам и Junior-позициям (Удаленно / Гибрид / Москва)
```
