# Spring-rest-api

## Техническое задание
Необходимо реализовать REST API  для социальной сети.

### Основные функции сервиса:

 - регистрация нового пользователя;
 - авторизация существующего пользователя;
 - пользователь может искать других пользователей;
 - пользователь может добавлять других пользователей в «друзья»;
 - пользователь может удалять других пользователей из «друзей»;
 - пользователь может получить список своих друзей;

### Технологический стек:

- java 11+;
- Spring;
- база данных для хранения данных пользователей(любая на выбор);
- UI реализовывать не требуется (можно использовать swagger);
- unit-tests (опционально);*

### Критерии завершения:
- Приложение написано и загружено в гит-репозиторий на проверку.
- Необходимо также подготовить инструкцию по запуску (README file).
- Опционально можно развернуть приложение на облачном сервисе (не обязательно).*

## Зависимости

* [Java 11 SDK](https://www.oracle.com/java/technologies/downloads/#java11)
* [Maven](https://maven.apache.org/download.cgi)

## Запуск

```bash
$ mvn spring-boot:run
```

Приложение будет работать по умолчанию на порту `8080`

Изменить настойки БД можно в __application.yml__
```
url: jdbc:postgresql://localhost:5432/postgres
username: postgres
password: {password}
```
