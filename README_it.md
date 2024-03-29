<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# httpsh on ttyd per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/httpsh.svg)](https://dash.yunohost.org/appci/app/httpsh) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/httpsh.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/httpsh.maintain.svg)

[![Installa httpsh on ttyd con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare httpsh on ttyd su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**Versione pubblicata:** 1.7.4~ynh3

## Screenshot

![Screenshot di httpsh on ttyd](./doc/screenshots/httpsh.png)

## Documentazione e risorse

- Documentazione ufficiale per gli amministratori: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Repository upstream del codice dell’app: <https://github.com/leshniak/httpsh>
- Store di YunoHost: <https://apps.yunohost.org/app/httpsh>
- Segnala un problema: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
o
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
