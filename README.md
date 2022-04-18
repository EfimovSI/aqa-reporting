Инструкция по настройке report portal (для Windows10):
1. Копировать файл docker-compose.yml по адресу https://github.com/reportportal/reportportal/blob/master/docker-compose.yml
2. Обновить / повторно развернуть приложение с помощью следующей команды в терминале: ```docker-compose -p reportportal up -d --force-recreate```
3. После ввода команды увидеть в логе часть сообщения: 
```\nThe Amazon CloudFront distribution is configured to block access from your country.\nWe can't connect to the server for this app or website at this time.```
4. Умыть руки :(