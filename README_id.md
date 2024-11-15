<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# httpsh on ttyd untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/httpsh.svg)](https://ci-apps.yunohost.org/ci/apps/httpsh/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/httpsh.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/httpsh.maintain.svg)

[![Pasang httpsh on ttyd dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang httpsh on ttyd secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**Versi terkirim:** 1.7.4~ynh4

## Tangkapan Layar

![Tangkapan Layar pada httpsh on ttyd](./doc/screenshots/httpsh.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- Depot kode aplikasi hulu: <https://github.com/leshniak/httpsh>
- Gudang YunoHost: <https://apps.yunohost.org/app/httpsh>
- Laporkan bug: <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
atau
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
