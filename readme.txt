Это маленький сервис по добавлению пользователя и получению данных всех пользователей. 
Запросы отправляю через Postman. Настроен 8081 порт, в application.properties можно его изменить. 
Используется СУБД H2 в серверном режиме

Команды:
GET: http://localhost:8081/api/users
POST: http://localhost:8081/api/users
{
    "name": "Олег Харитонов",
    "email": "john@example.com"
}
