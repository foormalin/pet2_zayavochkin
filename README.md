# pet2_zayavochkin
1. Проект "Заявочкин"

2. Заявочкин - система управления заявками на ремонт и обслуживание помещений.
Система автоматизирует процесс обработки заявок: от создания до закрытия с учетом SLA, ролей пользователей и контроля статусов.

3. Цель проекта - разработка полноценной системы обработки заявок. Разработка включает создание полной аналитической документации, REST API и последующей реализацией frontend/backend составляющих.

4. Основной функционал
> Регистрация и авторизация пользователей
> Создание заявок
> Назначение исполнителей
> Управление статусами заявок
> SLA-контроль
> Комментарии и вложения
> Уведомления
> Управление ролями пользователей

5. Роли
> USER - Создает заявки
> DISPATCHER - Назначает исполнителей
> EXECUTOR - выполняет заявки
> ADMIN - управляет системой

6. Архитектура
Система построена по клиент-серверной архитектуре.
Frontend взаимодействует с backend через REST API.
Backend обеспечивает обработку бизнес-логики, работу с SLA, управление заказами.

7. Структура репозитория
> docs/ - аналитическая документация
> api/ - OpenAPI спецификация
> frontend/ - frontend-составляющая
> backend/ - backend-составляющая
> database/ - SQL-скрипты и ERD
> deploy/ - docker и deployment конфиг
> tests/ - тестовая документация

8. Документация
Проект содержит полный набор аналитической документации,
описывающей бизнес-процессы, требования,
REST API и жизненный цикл заявок.

> [Vision](docs/vision/vision.md) - Цели системы, scope и ограничения 
> [Business Requirements (docs/business_requirements/business_requirements.md) - Бизнес-требования к системе 
> [Functional Requirements](docs/functional_requirements/functional_requirements.md) - Функциональные требования 
> [Non-Functional Requirements](docs/non_functional_requirements/nfr.md) - Нефункциональные требования
> [User Stories](docs/user_stories/user_stories.md) - Пользовательские истории 
> [Use Cases](docs/use_cases/README.md) - Сценарии взаимодействия пользователей с системой 
> [SLA](docs/sla/SLA.md) - SLA, эскалации и правила обработки заявок |
> [Business Rules](docs/business_rules/business_rules.md) - Бизнес-правила системы 
> [Error Handling](docs/error_handling/error_handling.md) - Правила обработки ошибок 
> [API Description](docs/api/api-description.md) - Описание REST API 
> [OpenAPI Specification](api/openapi.yaml) - OpenAPI 3.0 specification 
> [UML Diagrams](docs/uml/diagrams.md) - UML-диаграммы системы 
> [BPMN](docs/bpmn/README.md) - BPMN бизнес-процессы 
> [Data Model / ERD](docs/data_model/README.md) - Модель данных и ERD 
> [Acceptance Criteria](docs/acceptance_criteria.md) - Критерии приемки 
> [Backlog](docs/backlog.md) - MVP и roadmap проекта

9. Технологический стек
Документация
>Markdown
>OpenAPI 3.0
>PlantUML
>BPMN

Backend
> Python
> FastAPI
> SQLAlchemy
> PostgreSQL
> JWT Authentication

Frontend
> JavaScrypt
> React
> Vite
> Axios

Deployment
> Docker
