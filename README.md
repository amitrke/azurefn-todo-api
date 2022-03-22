API

POST /todo
{
    "todo": "I need to get grocery",
    "dueDate": "20220303T010101"
}

GET /todo
//Lists all todos
//Sample response
[{
    "id": "12323232323",
    "todo": "I need to get grocery",
    "dueDate": "20220303T010101",
    "status": 0
},
{
    "id": "12323232454",
    "todo": "I need to get grocery",
    "dueDate": "20220303T010101",
    "status": 0
},
{
    "id": "12323245434",
    "todo": "I need to get grocery",
    "dueDate": "20220303T010101",
    "status": 0
}]

POST /todo/{id}
{
    "id": "12323232323",
    "status": 1
}