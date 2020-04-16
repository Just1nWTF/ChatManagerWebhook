# ChatManagerWebhook
🐍Python webhook for [Чат-Менеджер](https://vk.com/cm).

## Сначала прочитайте эту статью: https://vk.com/@chatmanage-callback-api.

Зарегистрируйтесь на [PythonAnywhere](pythonanywhere.com) и создайте приложение на **Flask** с версией Python 3.7. Во вкладке Consoles с помощью pip установите библиотеку vk_api. Откройте Bash и напишите команду pip3.7 install --user vk-api (команду напишите вручную)
![alt text](example/image2.png) 
### Далее в /mysite нужно удалить все файлы и загрузите файл flask_app.py. Должно получиться так:
![alt text](example/image.png) 
После этого перезагрузите приложение. Ваш сервер готов. 
Теперь можно настроить вебхук по статье. 
Получите токен Чат-Менеджера и access_token от ВК. Затем делайте всё по статье выше и замените все данные в файле settings на свои.

`P.S. Если нашли баг - пишите в личные сообщения (https://vk.com/just1nwtf).`
