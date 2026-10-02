Пример приложения Quarkus, которое можно развернуть в Timeweb Cloud Apps без настройки.

🎉 [Демо]

🚀 [Создать свой Apps](https://timeweb.cloud/my/apps/create)

📚 [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
./mvnw dependency:resolve

# запуск в дев режиме
./mvnw quarkus:dev

# сборка для продакшн
./mvnw package && java -jar target/quarkus-app/quarkus-run.jar
```
