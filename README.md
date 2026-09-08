# ITOps Labs — Практические лабораторные работы по ITOps

Репозиторий содержит практические материалы для изучения ITOps (IT Operations).

## 📁 Структура проекта

```
it-ops-labs/
├── docs/                    # Документация
│   ├── roadmap/            # План обучения
│   ├── wiki/               # Справочные материалы
│   ├── knowledge-map/      # Карта знаний
│   └── tools/              # Документы по инструментам (uv, npm, nvm, fnm)
│
├── labs/                    # Практические занятия
│   ├── docker/             # Docker и Docker Compose
│   │   ├── networks/       # Сети в Docker
│   │   ├── ssh/            # SSH в контейнерах
│   │   ├── rsync/          # Rsync между контейнерами
│   │   ├── sftp/           # SFTP сервер
│   │   └── containers/     # Работа с образами (Debian, CentOS)
│   │
│   ├── nginx/              # Nginx настройка
│   │   ├── ssl/            # SSL конфигурация
│   │   └── certbot/        # Let's Encrypt сертификаты
│   │
│   ├── bases/              # Базы данных
│   │   ├── postgres/       # PostgreSQL
│   │   ├── mongo/          # MongoDB
│   │   └── redis/          # Redis
│   │
│   ├── text-editors/       # Текстовые редакторы
│   │   ├── nano/
│   │   ├── vim/
│   │   ├── micro/
│   │   └── helix/
│   │
│   ├── utilities/          # Полезные утилиты
│   │   ├── htop/
│   │   ├── btop/
│   │   └── mc/
│   │
│   ├── archivation/        # Архивация и бэкапы
│   │   ├── rsync/
│   │   └── tar/
│   │
│   ├── configs/            # Форматы конфигураций
│   │   ├── env/
│   │   ├── toml/
│   │   ├── json/
│   │   └── conf/
│   │
│   ├── linux-structure/    # Структура Linux
│   │
│   └── security/           # Информационная безопасность
│       ├── basics/
│       ├── firewall/
│       └── ssh-hardening/
│
├── projects/                # Примеры проектов
│   ├── nodejs/             # Node.js сервера
│   │   ├── basic-servers/  # Базовые HTTP/WebSocket сервера
│   │   └── pm2/            # PM2 process manager
│   ├── python/             # Python примеры
│   └── vendor/             # Сторонние проекты и исходники
│
├── scripts/                 # Вспомогательные скрипты
│
└── .github/                 # GitHub конфигурация
    └── templates/          # Шаблоны для issue/PR
```

## 🎯 Что внутри

### 📚 Документация (`docs/`)
- **Roadmap** — пошаговый план изучения тем от базовых к продвинутым
- **Wiki** — справочные материалы по каждой теме
- **Knowledge Map** — визуальная карта связей между темами
- **Tools** — руководства по инструментам разработки

### 🔬 Лабораторные работы (`labs/`)
Каждая лабораторная работа включает:
- Инструкцию по выполнению
- Конфигурационные файлы
- Тестовые окружения
- Проверочные задания

### 💻 Проекты (`projects/`)
- Готовые примеры серверов на Node.js
- Конфигурации PM2 для управления процессами
- Примеры на Python (опционально)
- Vendor проекты для изучения

## 🚀 Быстрый старт

1. Изучите [Roadmap](docs/roadmap/README.md) для понимания порядка изучения
2. Посмотрите [Карту знаний](docs/knowledge-map/README.md) для общего обзора
3. Выберите первую лабораторную работу в `labs/`
4. Следуйте инструкциям в README каждой лабы

## 📝 Форматы файлов

| Расширение | Назначение |
|------------|------------|
| `.md` | Документация, wiki, roadmap |
| `.json` | Конфигурации, данные |
| `.js` | Node.js проекты |
| `.py` | Python скрипты |
| `.yml/.yaml` | Docker Compose, конфигурации |
| `.env` | Переменные окружения |
| `.toml` | TOML конфигурации |
| `.conf` | Классические конфиги |
| `.sh` | Bash скрипты |

## 🔮 Планируемые расширения

- Monitoring (Prometheus, Grafana)
- CI/CD (GitHub Actions, GitLab CI)
- Configuration Management (Ansible)
- Cloud Basics (AWS/GCP/Azure)
- Logging (ELK Stack, Loki)

## 📋 Статус

Репозиторий находится в стадии инициализации. Темы будут раскрываться постепенно.

---

## 🤝 Contributing

Этот репозиторий создан для образовательных целей. 

---

*ITOps Labs — Практическое изучение IT Operations*
