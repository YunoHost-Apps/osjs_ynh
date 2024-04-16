<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# OSjs YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/osjs.svg)](https://dash.yunohost.org/appci/app/osjs) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/osjs.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/osjs.maintain.svg)

[![Instalatu OSjs YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osjs)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek OSjs YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

OS.js is an open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.


**Paketatutako bertsioa:** 3.1.12~ynh3

**Demoa:** <https://demo.os-js.org/>

## Pantaila-argazkiak

![OSjs(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.os-js.org>
- Administratzaileen dokumentazio ofiziala: <https://manual.os-js.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/os-js/OS.js>
- YunoHost Denda: <https://apps.yunohost.org/app/osjs>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/osjs_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/osjs_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
edo
sudo yunohost app upgrade osjs -u https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
