<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# CodiMD YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/codimd.svg)](https://ci-apps.yunohost.org/ci/apps/codimd/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)

[![Instalatu CodiMD YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=codimd)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek CodiMD YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

CodiMD is the free software version of HackMD, developed and opened source by the HackMD team with reduced features (without book mode), you can use CodiMD for your community and own all your data. [(See the origin of the name CodiMD.)](https://github.com/hackmdio/codimd/issues/720)

CodiMD is perfect for open communities, while HackMD emphasizes on permission and access controls for commercial use cases.

**Paketatutako bertsioa:** 2.5.4~ynh2

## Pantaila-argazkiak

![CodiMD(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://hackmd.io/>
- Erabiltzaileen dokumentazio ofiziala: <https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#User-Guides>
- Administratzaileen dokumentazio ofiziala: <https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#Administration-Guides>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/hackmdio/codimd>
- YunoHost Denda: <https://apps.yunohost.org/app/codimd>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/codimd_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
edo
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
