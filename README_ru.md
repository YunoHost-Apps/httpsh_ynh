<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# httpsh on ttyd для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/httpsh)](https://ci-apps.yunohost.org/ci/apps/httpsh/)
![Состояние работы](https://apps.yunohost.org/badge/state/httpsh)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/httpsh)

[![Установите httpsh on ttyd с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить httpsh on ttyd быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**Поставляемая версия:** 1.7.7~ynh1

## Снимки экрана

![Снимок экрана httpsh on ttyd](./doc/screenshots/httpsh.png)

## Документация и ресурсы

- Официальная документация администратора: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Репозиторий кода главной ветки приложения: <https://github.com/leshniak/httpsh>
- Магазин YunoHost: <https://apps.yunohost.org/app/httpsh>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
или
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
