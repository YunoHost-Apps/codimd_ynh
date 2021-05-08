# CodiMD pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Installer CodiMD avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=codimd)

> :warning: Le projet CodiMD a été renommé HedgeDoc. Le package YunoHost pour HedgeDoc est désormais hébergé à cette adresse https://github.com/YunoHost-Apps/hedgedoc_ynh. codimd_ynh restera à la version 1.6.0 et ne sera plus mis à jour.

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer CodiMD rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
CodiMD est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 2.3.2

## Captures d'écran

![](https://raw.githubusercontent.com/hackmdio/codimd/develop/public/screenshot.png)

## Démo

* [Démo officielle](https://demo.codimd.org/)

## Configuration

Vous pouvez configurer CodiMD en modifiant le fichier `/var/www/codimd/config.json` et en vous aidant de la [documentation](https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-configuration)

## Documentation

 * Documentation officielle : https://hackmd.io/c/codimd-documentation
 * Documentation YunoHost : https://yunohost.org/fr/app_codimd

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/codimd.svg)](https://ci-apps.yunohost.org/ci/apps/codimd/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/codimd.svg)](https://ci-apps-arm.yunohost.org/ci/apps/codimd/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/codimd_ynh/issues
 * Dépôt de l'application principale : https://github.com/hackmdio/codimd
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
ou
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```
it.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
ou
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```
