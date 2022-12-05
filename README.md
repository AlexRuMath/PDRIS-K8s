# PDRIS-K8s

Данные кофигурационные файлы были сконфигурированы для локальной ноды minikube. Для деплоя использовать следующие команды

```
kubectl apply -f .
```

Чтобы получить адрес подключения к сервису **для minikube**

```
minikube service client --url
```

Пример ответа по url:

```json
{
    "message": "OK",
    "data": [
        {
            "id": "638dc0ccbda01910c84b19a3",
            "name": "Alan",
            "age": 38
        },
        {
            "id": "638dc0ccbda01910c84b19a5",
            "name": "Johnathan",
            "age": 36
        },
        {
            "id": "638dc0ccbda01910c84b19a7",
            "name": "Lucy",
            "age": 47
        }
    ]
}
```