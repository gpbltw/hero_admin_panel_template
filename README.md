# React Redux приложение для панели администратора по созданию и управлению супергероями

## Описание

Веб-приложение представляет собой панель управления, с помощью которой можно добавлять супергероев с различными характеристиками и фильтровать их по элементам. Основная цель разработки — отработка навыков работы с собственной базой данных, которая хранит всех героев и информацию о них. При удалении персонажа данные корректно обновляются, а информация остаётся в базе данных на глобальном уровне и не теряется при перезапуске или закрытии приложения.

## Функционал

- Панель управления

Стандартная панель для создания новых супергероев.

![image](https://github.com/user-attachments/assets/e3655506-e803-4d40-8e21-caafbfd8217f)

Все поля формы должны быть заполнены, иначе будет отображаться соответствующее сообщение об ошибке.

![image](https://github.com/user-attachments/assets/71004491-cab7-4345-8282-3af0dd6d31b9)

После заполнения всех полей и нажатия кнопки "Создать", герой появляется в списке.

![Запись 2024-10-17 145002](https://github.com/user-attachments/assets/dc0cba5b-a9d8-49c9-a498-fcefd1320aff)

- Фильтрация

Позволяет фильтровать героев по их элементам.

![Запись 2024-10-17 145407](https://github.com/user-attachments/assets/459f8a37-52ec-4758-b923-82bb3802f38d)

- Работа с базой данных.

Приложение взаимодействует с базой данных, в которой хранятся все супергерои. Данные обновляются в реальном времени, сохраняясь при любых изменениях, таких как добавление или удаление персонажей.

![Запись 2024-10-17 150142](https://github.com/user-attachments/assets/125189b8-66d1-4f1b-b3d6-925f201852ad)

## Технологии
- ReactJS 18
- Redux Toolkit
- Custom hooks
- SCSS (стилизация)
- TransitionGroup
- uuid (генерация id)
- JSON (работа с базой данных)
