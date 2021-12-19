# Mirotalk-RUS-
Русифицированная версия ВКС Miratalk

`Бесплатные видеозвонки, чат и демонстрация экрана через браузер WebRTC`

<br>

[![Автор](https://img.shields.io/badge/Author-Miroslav-brightgreen.svg)](https://github.com/miroslavpejic85/mirotalk)
![License: AGPLv3](https://img.shields.io/badge/License-AGPLv3-blue.svg)

Работает на `WebRTC` с использованием Google Stun и [numb](http://numb.viagenie.ca/) Turn. MiroTalk обеспечивает качество видео и задержку, недоступную при использовании традиционных технологий.

## https://mirotalk.herokuapp.com/

## Демо

-   `Откройте` https://mirotalk.up.railway.app/newcall `или` https://mirotalk.herokuapp.com/newcall
-   `Выберите` индвидуальное название комнаты и `Присоединяйтесь к комнате`
-   `Разрешите` доступ к камере и микрофону
-   `Поделитесь` Ссылкой на комнату и `Подождите`, пока кто-нибудь не присоединится к конференции

## Присоединение к комнате

-   Вы также можете напрямую `присоединиться` к своей `комнате`, введя ссылку https://mirotalk.up.railway.app/join/имя-вашей-комнаты `или` https://mirotalk.herokuapp.com/join/имя-вашей-комнаты


## Docker

-   Установка https://docs.docker.com/compose/install/

```bash
# Скорируйте app/src/config.template.js в app/src/config.js и отредактируйте его, если это необходимо
$ cp app/src/config.template.js app/src/config.js
# Скорируйте docker-compose.template.yml в docker-compose.yml и отредактируйте его, если это необходимо
$ cp docker-compose.template.yml docker-compose.yml
# Создание или перестройка служб
$ docker-compose build
# Создание и запуск контейнеров
$ docker-compose up # -d
# Остановить и удалить ресурсы
$ docker-compose down
```

-   откройте http://localhost:3010 в браузере
