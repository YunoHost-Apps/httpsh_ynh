<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# httpsh on ttyd voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/httpsh)](https://ci-apps.yunohost.org/ci/apps/httpsh/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/httpsh)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/httpsh)

[![httpsh on ttyd met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je httpsh on ttyd snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**Geleverde versie:** 1.7.7~ynh1

## Schermafdrukken

![Schermafdrukken van httpsh on ttyd](./doc/screenshots/httpsh.png)

## Documentatie en bronnen

- Officiele beheerdersdocumentatie: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Upstream app codedepot: <https://github.com/leshniak/httpsh>
- YunoHost-store: <https://apps.yunohost.org/app/httpsh>
- Meld een bug: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
of
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
