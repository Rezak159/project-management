# Управление программными проектами

Лабораторные работы, ЮГУ, Инженерная школа цифровых технологий. Романов Глеб Сергеевич, ПИ41Б. Вариант 23 –
автоматизированная система учёта выдачи и возврата оборудования сотрудникам (АС УВО).

## ЛР № 1. Выявление, формализация и проверка требований

- [Lab1/Отчет_ЛР1_вариант23.pdf](Lab1/Отчет_ЛР1_вариант23.pdf) – отчёт
- [Lab1/ТЗ_вариант23.pdf](Lab1/ТЗ_вариант23.pdf) – техническое задание
- [Lab1/материалы](Lab1/материалы) – журнал интервью, первичное ТЗ, запросы и ответы агента

## ЛР № 2. Проектирование программной системы и формирование архитектурного контекста

- [Lab2/Отчет_ЛР2_вариант23.pdf](Lab2/Отчет_ЛР2_вариант23.pdf) – отчёт
- [Lab2/docs](Lab2/docs) – архитектурный контекст:
  - [requirements.md](Lab2/docs/requirements.md) – требования из ЛР № 1;
  - [project-context.md](Lab2/docs/project-context.md) – контекст, допущения, риски;
  - [use-cases.md](Lab2/docs/use-cases.md), [business-processes.md](Lab2/docs/business-processes.md),
    [data-model.md](Lab2/docs/data-model.md), [sequences.md](Lab2/docs/sequences.md) – диаграммы и пояснения;
  - [architecture.md](Lab2/docs/architecture.md) – компоненты, развёртывание, надёжность;
  - [adr](Lab2/docs/adr) – архитектурные решения ADR-001…006;
  - [policies.md](Lab2/docs/policies.md) – правила проекта;
  - [requirements-mapping.md](Lab2/docs/requirements-mapping.md) – соответствие требований проектным материалам;
  - [diagrams](Lab2/docs/diagrams) – исходники диаграмм (PlantUML, Mermaid, BPMN 2.0), изображения – в `images/`.
- [Lab2/reviews](Lab2/reviews) – проверка CLI-агентом Codex: [architecture-review.md](Lab2/reviews/architecture-review.md)
  (запросы и ответы), [review-decisions.md](Lab2/reviews/review-decisions.md) (решения по замечаниям), полные логи
  в `raw/`
- [Lab2/.agents/skills](Lab2/.agents/skills) – навыки агента и их источники

Теги: `v1` – материалы ЛР № 2 до проверки агентом, `v2` – итоговая версия.
