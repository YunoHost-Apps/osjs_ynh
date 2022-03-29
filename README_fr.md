# OSjs pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/osjs.svg)](https://dash.yunohost.org/appci/app/osjs) ![](https://ci-apps.yunohost.org/ci/badges/osjs.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/osjs.maintain.svg)  
[![Installer OSjs avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osjs)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer OSjs rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

[OS.js](https://www.os-js.org/) is an [open-source](https://raw.githubusercontent.com/os-js/OS.js/master/LICENSE) web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.


**Version incluse :** 3.1.12~ynh2

**Démo :** https://demo.os-js.org/

## Documentations et ressources

* Site officiel de l'app : https://www.os-js.org
* Documentation officielle de l'admin : https://manual.os-js.org/
* Dépôt de code officiel de l'app : https://github.com/os-js/OS.js
* Documentation YunoHost pour cette app : https://yunohost.org/app_osjs
* Signaler un bug : https://github.com/YunoHost-Apps/osjs_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/osjs_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
ou
sudo yunohost app upgrade osjs -u https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps