# parcel-cicd:
```
версия go: 1.22.5

```

## Работа над workflow:
```
Настройка автоматического тестирования и публикации приложения в DockerHub

```
## Описание работы:
```sh
Создал два `jobs`:
1. Первый проверяет код на наличие ошибок и запускать тесты;
2. Второй при добавлении тегов должен автоматически публиковать приложение в DockerHub.

```