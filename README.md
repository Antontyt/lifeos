# LifeOS

![Python](https://img.shields.io/badge/python-3.14-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-in%20development-yellow.svg)
![Tests](https://img.shields.io/badge/tests-pending-lightgrey.svg)

[Русский](#русский) | [English](#english)

---

## Русский

### О проекте

**LifeOS** — персональная система управления жизнью, объединяющая в одном
инструменте:

- 💰 **Управление финансами** — учёт доходов и расходов, бюджетирование
- 📋 **Kanban-доска** — визуальное планирование задач и проектов
- ✅ **Трекер привычек** — отслеживание регулярных действий и прогресса
- 🎯 **Стратегии развития** — постановка и отслеживание долгосрочных целей

Проект переработан с нуля с применением современных практик Python-разработки
и DevOps: автоматизированное тестирование, статический анализ кода,
контейнеризация, CI/CD.

### Стек технологий


| Категория | Инструмент |
|---|---|
| Язык | Python 3.14 |
| Тестирование | pytest, pytest-cov |
| Линтинг и форматирование | ruff |
| Проверка типов | mypy |
| CI/CD | GitHub Actions |
| Контейнеризация | Docker |


### Установка

\`\`\`bash
git clone https://github.com/Antontyt/lifeos.git
cd lifeos
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
\`\`\`

### Разработка

\`\`\`bash
# Запуск тестов
pytest

# Проверка линтером
ruff check .

# Проверка типов
mypy .
\`\`\`

### Лицензия

MIT — см. файл [LICENSE](LICENSE)

---

## English

### About

**LifeOS** is a personal life management system that brings together:

- 💰 **Finance management** — income and expense tracking, budgeting
- 📋 **Kanban board** — visual task and project planning
- ✅ **Habit tracker** — monitoring recurring actions and progress
- 🎯 **Development strategies** — setting and tracking long-term goals

The project has been rebuilt from scratch applying modern Python development
and DevOps practices: automated testing, static code analysis,
containerization, and CI/CD.

### Tech Stack


| Category | Tool |
|---|---|
| Language | Python 3.14 |
| Testing | pytest, pytest-cov |
| Linting & formatting | ruff |
| Type checking | mypy |
| CI/CD | GitHub Actions |
| Containerization | Docker |


### Installation

\`\`\`bash
git clone https://github.com/Antontyt/lifeos.git
cd lifeos
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
\`\`\`

### Development

\`\`\`bash
# Run tests
pytest

# Lint check
ruff check .

# Type check
mypy .
\`\`\`

### License

MIT — see [LICENSE](LICENSE) file
