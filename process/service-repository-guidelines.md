# Правила сервисных репозиториев

## 1. Именование репозиториев

- Только строчные буквы
- Слова разделяются дефисом
- Примеры: order-service, payment-service, api-gateway

## 2. Ветки

В каждом сервисном репозитории обязательны ветки:
- dev (основная)
- test
- prod

Default branch = dev

## 3. Сообщения коммитов

Используем Conventional Commits:

- feat: новая функциональность
- fix: исправление ошибки
- docs: документация
- chore: технические изменения (зависимости, конфиги)
- refactor: рефакторинг
- test: тесты

Примеры:
feat: add create order endpoint
fix: correct order status transition
docs: update README

## 4. Базовая структура сервиса (целевая)

src/main/java/... 
src/main/resources/
  - application.yml
  - db/migration/          (Flyway)
  - openapi/               (OpenAPI-спецификации)
src/test/java/...
Dockerfile
README.md
.gitignore
