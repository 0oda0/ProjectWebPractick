# ProjectWebPractick

# Канбан-доска на ASP.NET Core

## Описание проекта
Веб-приложение для управления задачами по методологии Kanban, разработанное с использованием ASP.NET Core. Проект реализует основные функции Kanban-доски:
- Создание и управление задачами
- Распределение задач по колонкам
- Отслеживание статуса выполнения
- Визуализация рабочего процесса

## Технические требования
- .NET 6.0 или выше
- ASP.NET Core
- Entity Framework Core
- SQL Server или совместимая база данных
- Веб-браузер с поддержкой HTML5

## Установка
1. Клонируйте репозиторий:
```bash
git clone https://github.com/0oda0/ProjectWebPractick.git
```

2. Установите зависимости:
```bash
dotnet restore
```

3. Настройте подключение к базе данных в appsettings.json

4. Запустите миграцию:
```bash
dotnet ef database update
```

5. Запустите приложение:
```bash
dotnet run
```

## Функциональные возможности
- Добавление/удаление колонок
- Создание/редактирование карточек
- Перемещение задач между колонками
- Назначение исполнителей
- Установка сроков выполнения
- История изменений

## Структура проекта
```
/KanbanBoard
│   .gitignore
│   README.md
│   appsettings.json
│
├───Controllers
├───Data
├───Models
├───Views
└───wwwroot
```

## Автор
- **Олейник Данил**  
  Группа: БПИ 2403

## Лицензия
[MIT License](https://choosealicense.com/licenses/mit/)

## Контакты
- GitHub: [0ada0](https://github.com/0oda0)
- Email: [0airone0@gmail.com]

## Вклад в проект
При обнаружении ошибок или предложений по улучшению, пожалуйста, создайте issue или отправьте pull request.

## Благодарности
- Команда ASP.NET за создание отличной платформы для разработки
- Сообщество GitHub за поддержку и вдохновение

## Roadmap
- [ ] Добавление комментариев к задачам
- [ ] Система уведомлений
- [ ] Экспорт данных
- [ ] Мобильная версия
- [ ] Интеграция с календарем

## Известные ограничения
- Поддержка только одного проекта
- Базовая аутентификация
- Отсутствие экспорта данных

## Инструкции по использованию
1. Создайте новый проект
2. Добавьте колонки
3. Создайте задачи
4. Назначьте исполнителей
5. Отслеживайте прогресс

## Тестирование
Для запуска тестов:
```bash
dotnet test
```

## Документация
- [Документация ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/)
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)

## Полезные ссылки
- [Методология Kanban](https://kanbanize.com/kanban-method)
- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)
