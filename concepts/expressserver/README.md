# Запуск сервера

Устанавливаем фреймворк **Express**
```
npm install
```

Запускаем программу

```
npm start
```

Запускаем браузер и вбиваем в адресную строку

```
http://localhost:5015/calculate/sum?a=12&b=6
```

В браузере появится следующий ответ

```
{"result":18}
```

Таким образом, мы смогли запустить сервер на порте и написали код для приёма и обработки запроса типа **GET**

# Работа с формами

Запускаем программу

```
npm start
```

Заходим через браузер по адресу

```
http://localhost:5015/me/page?htmlpage=good.html
```

Получаем страницу с двумя полями ввода и кнопкой

Вбиваем в поля ввода числа и нажимаем на кнопку *"Отправить запрос"*

После этого перед нами появится результат вычисления суммы чисел