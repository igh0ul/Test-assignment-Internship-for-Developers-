# Test-assignment-Internship-for-Developers-
***
## task_1
В этом файле представлен список багов найденных на скриншоте страницы Avito Team
***

## TESTCASES.md 
Этот файл содержит тесткейсы на пользовательские сценарии:
- создание задачи 
- открытие карточки товара 
- поиск задачи
- переход на доску проекта
 и их автоматизированные версии (E-2E)

- Тесты написаны на Python (Playwright + Pytest*)

**инструкции по запуску**
Запустить все тесты: pytest -s -v

Запустить конкретный файл: pytest tests/test_create_task.py -s -v

Запустить определённый тест: pytest -k test_create_task_valid -s -v

Установка: pip install -r requirements.txt
playwright install




***