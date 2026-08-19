# Тестирование Fake Store API - Products

Проект по ручному тестированию публичного API [fakestoreapi.com](https://fakestoreapi.com/). Цель - применить навыки ручного тестирования API на практике: составление тест-плана, тест-дизайн с применением техник (Equivalence Partitioning, Boundary Value Analysis, Error Guessing), выполнение тест-кейсов через Postman, оформление баг-репортов.

## Инструменты

- Postman - ручное тестирование API
- Тестируемый API: fakestoreapi.com (ресурс Products)

## Структура проекта

| Файл | Содержание |
|---|---|
| `test-plan.md` | План тестирования (цели, область, стратегия, риски) |
| `checklist.md` | Чек-лист проверок по каждому эндпоинту |
| `test-cases.md` | 27 тест-кейсов (GET, POST, PUT, DELETE /products) |
| `bug-reports.md` | 4 баг-репорта со скриншотами |
| `observations.md` | Наблюдения о системных закономерностях в поведении API |
| `test-summary-report.md` | Итоговый отчёт по результатам тестирования |
| `Fake Store API - Products Testing.postman_collection.json` | Экспортированная коллекция Postman со всеми запросами |
| `screenshots/` | Скриншоты к баг-репортам |

## Результаты

- 27 тест-кейсов, все Passed
- Найдено 4 дефекта, связанных с отсутствием серверной валидации входных данных и проверки существования ресурса при обращении по id

Подробности в `test-summary-report.md`.
