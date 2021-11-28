# Miratalk-RUS-
Русифицированная версия ВКС Miratalk

`Бесплатные видеозвонки, чат и демонстрация экрана через браузер WebRTC`

<br>

[![Автор](https://img.shields.io/badge/Author-Miroslav-brightgreen.svg)](https://github.com/miroslavpejic85/mirotalk)
![License: AGPLv3](https://img.shields.io/badge/License-AGPLv3-blue.svg)

Работает на `WebRTC` с использованием Google Stun и [numb](http://numb.viagenie.ca/) Turn. MiroTalk обеспечивает качество видео и задержку, недоступную при использовании традиционных технологий.

## https://mirotalk.herokuapp.com/

## Demo

-   `Open` https://mirotalk.up.railway.app/newcall `or` https://mirotalk.herokuapp.com/newcall
-   `Pick` your personal Room name and `Join To Room`
-   `Allow` to use the camera and microphone
-   `Share` the Room URL and `Wait` someone to join for video conference

## Room join

-   You can also `join` directly to your `room` by going to https://mirotalk.up.railway.app/join/your-room-name-goes-here `or` https://mirotalk.herokuapp.com/join/your-room-name-goes-here


---

## Docker

-   Install https://docs.docker.com/compose/install/

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

-   Open http://localhost:3000 in browser

---
