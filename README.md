# tg-bot-go-shortlink

https://t.me/ShortlinksQR_bot

Учебный проект на golang по созданию telegram бота

# Ожидаемый функционал:

На вход __*пользователь*__ дает 
* ссылка (пример: <https://github.com/xoloshef> или [github.com](https://github.com/xoloshef/tg-bot-go-shortlink/ "ссылка на проект tg-bot-go-shortlink") )

На выход __*telegram_bot*__ дает 
* сокращенную ссылку
* QR код
* у обработанной ссылки есть стандартное время хранения (сутки)
* пользователь может настроить время хранения ссылки дополнительным параметром

# Используеться:
* Golang 1.21.6
* PostgreSQL 16
* Golang-telegram-bot-api v5.5.1

# Ссылки
* стороняя библеотека от сообщества - https://github.com/go-telegram-bot-api/telegram-bot-api
* 

Может понадобиться

```
- go get -u github.com/go-telegram-bot-api/telegram-bot-api
```