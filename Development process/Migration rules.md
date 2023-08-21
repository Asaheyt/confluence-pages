# Liquibase — это система управления миграциями базы данных.  

Версионность приложения должна быть отражена в структуре папок миграций. 

```
/db-migrations
    /v-1.0
        /2023-08-21--01-initial-schema.sql
        /2023-08-21--02-alter-table-users.sql
        /changelog-v.1.0-cumulative.xml
    /v-2.0
        ...
        /changelog-v.2.0-cumulative.xml
    /changelog.xml
```

## [Подробнее см. habr](https://habr.com/ru/articles/179425/)  

