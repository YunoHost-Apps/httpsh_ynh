<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 httpsh on ttyd

[![集成程度](https://apps.yunohost.org/badge/integration/httpsh)](https://ci-apps.yunohost.org/ci/apps/httpsh/)
![工作状态](https://apps.yunohost.org/badge/state/httpsh)
![维护状态](https://apps.yunohost.org/badge/maintained/httpsh)

[![使用 YunoHost 安装 httpsh on ttyd](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=httpsh)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 httpsh on ttyd。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

This package is based on two projects:

* [ttyd](https://tsl0922.github.io/ttyd) is a TTY (terminal) web server
* [httpsh](https://github.com/leshniak/httpsh) is a login script that is called by ttyd


**分发版本：** 1.7.7~ynh1

## 截图

![httpsh on ttyd 的截图](./doc/screenshots/httpsh.png)

## 文档与资源

- 官方管理文档： <https://github.com/tsl0922/ttyd/wiki/Example-Usage>
- 上游应用代码库： <https://github.com/leshniak/httpsh>
- YunoHost 商店： <https://apps.yunohost.org/app/httpsh>
- 报告 bug： <https://github.com/YunoHost-Apps/httpsh_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
或
sudo yunohost app upgrade httpsh -u https://github.com/YunoHost-Apps/httpsh_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
