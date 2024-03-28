<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# httpsh on ttyd pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/httpsh.svg)](https://dash.yunohost.org/appci/app/httpsh) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/httpsh.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/httpsh.maintain.svg)

[![Installer httpsh on ttyd avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer httpsh on ttyd rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Ce paquet est basé sur deux projets :
* [ttyd](https://tsl0922.github.io/ttyd) est un serveur web TTY (terminal)
* [httpsh](https://github.com/leshniak/httpsh) est un script de connection appelé par ttyd


**Version incluse :** 1.7.4~ynh3

## Captures d’écran

![Capture d’écran de httpsh on ttyd](./doc/screenshots/httpsh.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Dépôt de code officiel de l’app : <https://github.com/leshniak/httpsh>
- YunoHost Store : <https://apps.yunohost.org/app/httpsh>
- Signaler un bug : <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
ou
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
