# CodiMD pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Installer CodiMD avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=codimd)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer CodiMD rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Éditeur collaboratif pour travailler sur des notes en Markdown

**Version incluse :** 2.4.1~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

### Configuration

You can configure CodiMD by editing this file `/var/www/codimd/config.json` using the [documentation](https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-configuration)

## Documentations et ressources

* Site officiel de l'app : https://hackmd.io/
* Documentation officielle utilisateur : https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#User-Guides
* Documentation officielle de l'admin : https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#Administration-Guides
* Dépôt de code officiel de l'app : https://github.com/hackmdio/codimd
* Documentation YunoHost pour cette app : https://yunohost.org/app_codimd
* Signaler un bug : https://github.com/YunoHost-Apps/codimd_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
ou
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps