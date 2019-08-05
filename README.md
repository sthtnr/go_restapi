# Implemention of simple API with golang!

#### Get all todos
`GET /todo-list/`

#### Get todo
`GET /todo-list/:task_number`

#### Create todo
`POST /todo-list/create-todo`

### Request example
```json
{
    "task_number": "1",
    "content": "practice piano hard :3",
    "deadline": "2019/08/02"
}
```

#### Update todo
`PUT /todo-list/update-todo/:task_number`

#### Delete todo
`DELETE /todo-list/delete-todo/:task_number`

## References
https://github.com/bradtraversy/go_restapi






