# Miratalk-RUS-
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


---

## Docker

-   Установка https://docs.docker.com/compose/install/

```bash
# copy .env.template to .env
$ cp .env.template .env
# build or rebuild services
$ docker-compose build
# create and start containers
$ docker-compose up # -d
# stop and remove resources
$ docker-compose down
```

-   откройте http://localhost:3000 в браузере

---
