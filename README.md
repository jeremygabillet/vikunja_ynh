<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Vikunja for YunoHost

[![Integration level](https://dash.yunohost.org/integration/vikunja.svg)](https://dash.yunohost.org/appci/app/vikunja) ![](https://ci-apps.yunohost.org/ci/badges/vikunja.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/vikunja.maintain.svg)  
[![Install Vikunja with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Vikunja quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Self-hosted To-Do list application

**Shipped version:** 0.18.1~ynh1

**Demo:** https://try.vikunja.io/login

## Screenshots

![](./doc/screenshots/kanban.png)

## Disclaimers / important information

## Configuration

You can also configure Vikunja by editing this file `/opt/vikunja/config.yml` using the [documentation](https://vikunja.io/docs/config-options/).


The API is accesible with this path: https://domain.ltd/api/v1/docs
## Documentation and resources

* Official app website: https://vikunja.io/
* Official admin documentation: https://vikunja.io/docs/
* Upstream app code repository: https://kolaente.dev/vikunja/
* YunoHost documentation for this app: https://yunohost.org/app_vikunja
* Report a bug: https://github.com/YunoHost-Apps/vikunja_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
or
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps