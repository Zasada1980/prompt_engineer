# Prompt Engineer GPT – Repository

Этот репозиторий содержит все настройки и файлы знаний для кастомного GPT-агента «Промт-Инженер / Prompt Engineer».

## Структура

- `system_instructions/prompt_engineer_instructions.md`  
  Системные инструкции агента. Этот текст нужно вставлять в поле **Instructions** при настройке Custom GPT в ChatGPT.

- `knowledge/`  
  Тематические файлы знаний, которые загружаются в раздел **Knowledge**:
  - `01_Guide_Prompt_Techniques.md` – справочник по техникам промт-инжиниринга.
  - `02_Checklists.md` – чек-листы (качество промпта, безопасность, дизайн workflow).
  - `03_Examples_and_Templates.md` – примеры и шаблоны промптов.
  - `04_FAQ.md` – часто задаваемые вопросы.
  - `05_Glossary.md` – словарь терминов (RU/EN).

- `procedures/`  
  Файлы с процедурами и инструкциями для пользователя:
  - `Setup_GPT_Instructions.md` – как настроить и запустить агента.
  - `Update_Process.md` – как обновлять инструкции и knowledge-файлы.

- `actions_specs/`  
  Спецификации Custom Actions для интеграции с внешними сервисами:
  - `prompt_repository_api.yaml` – пример API для репозитория промптов.

- `meta/`  
  Служебная информация:
  - `CHANGELOG.md` – журнал изменений (версии, даты, комментарии).

## Быстрый старт

1. Откройте `system_instructions/prompt_engineer_instructions.md` и скопируйте его содержимое в поле **Instructions** вашего Custom GPT в ChatGPT.
2. Загрузите все файлы из папки `knowledge/` в раздел **Knowledge** этого GPT.
3. При необходимости настройте Custom Actions по спецификации из `actions_specs/prompt_repository_api.yaml`.
4. Следуйте шагам в `procedures/Setup_GPT_Instructions.md`, чтобы протестировать агента и убедиться, что он работает как ожидается.
