Приложение клиент-сервер для скачивания легковесных дистрибутивов Linux

How-to-use   
Для локального запуска  
1. Запустить в директории `npm install`
2. Поменять значения количества потоков и ограничения скорости закачки (в кб/с) сервера в файле `.env`
3. В файле `client.js` проверить IP адрес сервера, должно быть
```const serverIp = "localhost"```
4. Запускаем сервер `nodemon server.js`
5. Открываем `index.html` в браузере