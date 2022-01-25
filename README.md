# Документация по API 

Главный эндпоинт:\
`https://api.maxthetomas.ru/`

<br>

## Метод авторизации
Авторизация происходит через HTTP-заголовок `Authorization`.\
Для бота используется заголовок типа:\
`Authorization: Bot %TOKEN%`\
*%TOKEN%* - Токен бота в Base-64

<br>

## Создание приложений
![Открыть меню приложений](https://cdn.discordapp.com/attachments/870348017809620992/935453309148467270/unknown.png)
![Нажать "Создать"](https://cdn.discordapp.com/attachments/870348017809620992/935453453784870932/unknown.png)
![Включить бота](https://cdn.discordapp.com/attachments/870348017809620992/935453540648894524/unknown.png)

<br>

## Модули

| Эндпоинт | Описание | 
| --- | ----- | 
| [`/files`](/api/files) | Загрузка / Изменение файлов | 
| [`/events`](/api/events) | Ивенты | 
| [`/notices`](/api/notices) | Объявления (заметки) | 
| [`/schedule`](/api/schedule) | Расписание | 
| [`/courses`](/api/courses) | Курсы | 

<!-- [`/events` Ивенты](/api/files)\ -->