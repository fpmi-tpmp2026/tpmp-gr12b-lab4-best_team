# Project Name: Пушной аукцион

## Description

Консольное приложение на C/C++ для автоматизации деятельности пушного аукциона. Система позволяет управлять зверофермами, учитывать выставленную на торги пушнину, фиксировать результаты продаж и формировать финансовую отчетность. Приложение использует базу данных SQLite.

## Installation

1. Клонировать репозиторий с кодом:

   `git clone https://github.com/Cloudy680/tpmp-lab4-rep2.git`

   `cd tpmp-lab4-rep2`

2. Установить SQLite3 и компилятор (для Ubuntu/Debian):

   `sudo apt-get install sqlite3 libsqlite3-dev g++ make`

3. Собрать проект:

   `make`

4. Инициализировать базу данных:

   `sqlite3 auction.db < FurAuction_create.sql`

## Usage

Запуск приложения:

`./bin/app`

**Роли пользователей:**

- Администратор (Управление зверосовхозами) — полный доступ ко всем операциям.
- Звероферма — доступ только к своим лотам и своей прибыли (ввод номера фермы).

**Основные функции:**

- Управление зверофермами (CRUD)
- Приёмка пушнины на аукцион (CRUD лотов)
- Фиксация результатов торгов
- Просмотр общей статистики
- Просмотр своих лотов (для фермы)
- Просмотр своей прибыли (для фермы)

## Contributing

**Авторы проекта:**

- **Янушкевич Максим** (Team Lead) — проектирование базы данных (Vertabelo), ведение wiki, GitHub Pages, управление репозиторием.
- **Вороненко Константин** — разработка кода приложения, Unit-тесты, настройка CI/CD (GitHub Actions).
- **Макоско Алексей** — проектирование UML-диаграмм (Use Case, Class, Activity, Sequence, Components).

**Ссылки:**

- Wiki проекта (документация): https://github.com/fpmi-tpmp2026/tpmp-gr12b-lab4-best_team/wiki
- Репозиторий с кодом: https://github.com/Cloudy680/tpmp-lab4-rep2
- GitHub Pages: https://cloudy680.github.io/tpmp-lab4-rep2/
- Отчет: https://docs.google.com/document/d/1QR6z-7NldxU-agGrCXdBcYUmEzBu9sPk/edit?usp=sharing&ouid=115522212482991015873&rtpof=true&sd=true
