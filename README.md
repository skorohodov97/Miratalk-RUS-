# Mirotalk-RUS
Русифицированная версия ВКС Miratalk

`Бесплатные видеозвонки, чат и демонстрация экрана через браузер WebRTC`

<br>

Работает на `WebRTC` с использованием Google Stun и [numb](http://numb.viagenie.ca/) Turn. MiroTalk обеспечивает качество видео и задержку, недоступную при использовании традиционных технологий.

<br>

-   `Откройте` https://sfu.mirotalk.org/
-   `Выберите` индвидуальное название комнаты и `Присоединяйтесь к комнате`
-   `Разрешите` доступ к камере и микрофону
-   `Поделитесь` Ссылкой на комнату и `Подождите`, пока кто-нибудь не присоединится к конференции



## Docker

-   Установите docker engine: https://docs.docker.com/engine/install/
-   Установите docker compose: https://docs.docker.com/compose/install/

```bash
# Copy app/src/config.template.js in app/src/config.js and edit it if needed
$ cp app/src/config.template.js app/src/config.js
# Copy docker-compose.template.yml in docker-compose.yml and edit it if needed
$ cp docker-compose.template.yml docker-compose.yml
# Build or rebuild services
$ docker-compose build
# Create and start containers
$ docker-compose up # -d
# Stop and remove resources
$ docker-compose down
```

-   Откройте https://localhost:3010 в браузере

---

<br>

### Автор

https://github.com/miroslavpejic85/mirotalksfu
