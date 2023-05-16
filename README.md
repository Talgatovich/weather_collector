# weather_collector
#### Коллектор для https://openweathermap.org/, который каждый час собирает информацию о погоде для 50 крупнейших городов мира, после чего сохраняет значение в БД
___
### Запуск:
1. Склонировать репозиторий

```
git clone git@github.com:Talgatovich/weather_collector.git
```

2. Создать файл .env и добавить туда строку
```
API_KEY=<Ваш API ключ для https://openweathermap.org/>
```
3. В терминале запустить команду
``` 
docker-compose up
```


___
Автор: [Ибятов Раиль](https://github.com/Talgatovich)
