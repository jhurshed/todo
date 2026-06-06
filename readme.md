# cli todo app

## функционал 
1. создание задач
2. получение всех задач
3. получение по id
4. обновление по id
5. удаление по id

### хранилище struct

```go
type Todo struct {
    ID          int
    Title       string
    Description string
    IsDone      bool
    CreatedAt   time.Time
    UpdatedAt   time.Time
}
```

