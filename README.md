# CRUDL операции:
- Создайте приложение которое будет использовать данные из бэкенда
- Дизайн не важен, важна функциональность

## Функции
- Страница со списком всех записей
- Страница создания новой записи
- Страница для 1 конкретной записи
- Обновление значения text у конкретной записи
- Удаление конкретной записи

## API endpoints
- POST https://artem-test-8c652-default-rtdb.firebaseio.com/test.json {"user_id" : "jack", "text" : "Ahoy!"} - создать
- GET https://artem-test-8c652-default-rtdb.firebaseio.com/test.json - получить все
- GET https://artem-test-8c652-default-rtdb.firebaseio.com/test/<id>.json - получить конкретный
- PUT https://artem-test-8c652-default-rtdb.firebaseio.com/test/<id>.json - обновить
- DELETE https://artem-test-8c652-default-rtdb.firebaseio.com/test/<id>.json - удалить
