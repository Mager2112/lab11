# lab11
**ngrok** - утилита для создания удалённого доступа к localhost. Он предназначен для коммуникации разработчиков. Нарпример, можно ввести команду:

*ngrok http 8080* - запуск локального порта

Для того, чтобы им пользоваться, нужно зарегестрироваться на сайте и получить токен.

## Как он работает ##

Вы загружаете и запускаете программу, затем указываете порт сетевой службы, обычно это веб-сервер.

Программа подключается к облачной службе ngrok, которая выдаёт вам сгенерированный адрес (домен третьего уровня). Если открыть этот адрес в веб-браузере, то трафик будет перенаправлен на вашу локальную сетевую службу или на любой адрес, который вы указали.
