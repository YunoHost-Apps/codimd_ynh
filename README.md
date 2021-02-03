# CodiMD for YunoHost

[![Integration level](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Install CodiMD with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=codimd)

> :warning: The CodiMD project has been renamed HedgeDoc. The YunoHost package for HedgeDoc is now hosted at this address https://github.com/YunoHost-Apps/hedgedoc_ynh. codimd_ynh will stay at version 1.6.0 and will no longer be updated.

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install CodiMD quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
CodiMD is a real-time collaborative word processing web service. It uses Markdown language.

**Shipped version:** 1.6.0

**Important note :**  the former CodiMD software (fork of HackMD) has been renamed HedgeDoc, while the previous HackMD software was renamed CodiMD.
For the moment, for compatibility reason this package is still called CodiMD, but **the software installed is HedgeDoc**.
See https://hedgedoc.org/history/ for more information about it.


## Screenshots

![](https://demo.codimd.org/screenshot.png)

## Demo

* [Official demo](https://demo.codimd.org/)

## Configuration

You can configure CodiMD by editing this file `/var/www/codimd/config.json` using the [documentation](https://github.com/codimd/server/blob/master/docs/configuration.md)

## Documentation

 * Official documentation: https://github.com/hedgedoc/hedgedoc/tree/master/docs
 * YunoHost documentation: https://yunohost.org/#/app_codimd

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/codimd/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/codimd/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/codimd_ynh/issues
 * Upstream app repository: https://github.com/hedgedoc/hedgedoc
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
or
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```
