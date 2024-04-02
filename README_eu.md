<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# httpsh on ttyd YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/httpsh.svg)](https://dash.yunohost.org/appci/app/httpsh) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/httpsh.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/httpsh.maintain.svg)

[![Instalatu httpsh on ttyd YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek httpsh on ttyd YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**Paketatutako bertsioa:** 1.7.4~ynh3

## Pantaila-argazkiak

![httpsh on ttyd(r)en pantaila-argazkia](./doc/screenshots/httpsh.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/leshniak/httpsh>
- YunoHost Denda: <https://apps.yunohost.org/app/httpsh>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
edo
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
