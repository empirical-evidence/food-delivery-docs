# Food Delivery Platform — Documentation

Репозиторий содержит всю проектную и процессную документацию Food Delivery Platform.

## Структура

food-delivery-docs/
├── PROJECT_CONTEXT.md              # Актуальный контекст проекта
├── process/
│   ├── definition-of-ready.md      # Definition of Ready
│   ├── definition-of-done.md       # Definition of Done
│   └── documentation-guidelines.md # Правила работы с документацией
├── adr/
│   ├── README.md                   # Как вести ADR
│   ├── ADR-001-multi-repo.md
│   ├── ADR-002-api-first-openapi.md
│   ├── ADR-003-kafka-as-message-broker.md
│   ├── ADR-004-openfeign-resilience4j.md
│   ├── ADR-005-postgresql-flyway.md
│   └── ADR-006-java21-spring-boot3.md
├── architecture/                   # Архитектурные схемы (C4 и др.)
└── templates/
└── adr-template.md             # Шаблон для новых ADR


## С чего начать новому участнику

1. Прочитай [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md)
2. Ознакомься с [Definition of Ready](process/definition-of-ready.md) и [Definition of Done](process/definition-of-done.md)
3. Просмотри принятые архитектурные решения в папке [adr/](adr/)
4. Прочитай [правила работы с документацией](process/documentation-guidelines.md)

## Как вносить изменения

Все изменения вносятся через Pull Request.  
Документация является частью процесса разработки и поддерживается в актуальном состоянии.

## Текущий статус

**Sprint 0 — Этап 1 завершён**  
Документация и процессные артефакты подготовлены.
