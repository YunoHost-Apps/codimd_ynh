# CodiMD pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Installer CodiMD avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=codimd)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer CodiMD rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble
Éditeur collaboratif pour travailler sur des notes en Markdown.

**Version incluse:** 1.6.0

## Captures d’écran

![](https://demo.codimd.org/screenshot.png)

## Démo

* [Démo officielle](https://demo.codimd.org/)

## Configuration

Si vous voulez configurer CodiMD, vous pouvez modifier votre fichier `/var/www/codimd/config.json` en vous aidant de la [documentation](https://github.com/codimd/server/blob/master/docs/configuration-config-file.md)

## Documentation

 * Documentation officielle : https://hackmd.io/c/codimd-documentation/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n’hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

* L’authentification LDAP est-elle prise en charge ? Non
* L’application peut-elle être utilisée par plusieurs utilisateurs ? Oui

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/codimd/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/codimd%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/codimd/)

## Limitations

**Statut** : En cours, ne *pas encore* considérer cette application comme stable et fonctionnant. 

## Informations additionnelles

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/codimd_ynh/issues
 * Dépôt de l’application principale : https://github.com/codimd/server/
 * Site web YunoHost : https://yunohost.org/

---

Informations pour les développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
ou
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```
