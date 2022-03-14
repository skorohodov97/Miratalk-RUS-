# Mirotalk-RUS-
Русифицированная версия ВКС Miratalk

`Бесплатные видеозвонки, чат и демонстрация экрана через браузер WebRTC`

<br>



Работает от `WebRTC` встроенного сервера SFU и SFU.

Откройте приложение со следующими поддерживаемыми браузерами и многими другими...

## https://sfu.mirotalk.org/

## Демо

-   `Откройте` https://sfu.mirotalk.org/
-   `Выберите` индвидуальное название комнаты и `Присоединяйтесь к комнате`
-   `Разрешите` доступ к камере и микрофону
-   `Поделитесь` Ссылкой на комнату и `Подождите`, пока кто-нибудь не присоединится к конференции

## Присоединение к комнате

-   Вы также можете напрямую `присоединиться` к своей `комнате`, введя ссылку https://sfu.mirotalk.org/

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
-   
