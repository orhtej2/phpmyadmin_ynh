<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# phpMyAdmin pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/phpmyadmin.svg)](https://dash.yunohost.org/appci/app/phpmyadmin) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/phpmyadmin.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/phpmyadmin.maintain.svg)

[![Installer phpMyAdmin avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpmyadmin)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer phpMyAdmin rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Application web de gestion des bases de données MySQL

**Version incluse :** 5.1.3~ynh1

**Démo :** https://demo.phpmyadmin.net/master-config

## Captures d’écran

![Capture d’écran de phpMyAdmin](./doc/screenshots/68747470733a2f2f7777772e7068706d7961646d696e2e6e65742f7374617469632f696d616765732f73637265656e73686f74732f7374727563747572652e706e67.png)

## Avertissements / informations importantes

## Vue d'ensemble

phpMyAdmin est un outil logiciel libre écrit en PHP, destiné à gérer l'administration de MySQL sur le Web. phpMyAdmin prend en charge un large éventail d'opérations sur MySQL et MariaDB. Les opérations fréquemment utilisées (gestion des bases de données, des tables, des colonnes, des relations, des index, des utilisateurs, des autorisations, etc.) peuvent être effectuées via l'interface utilisateur, tandis que vous avez toujours la possibilité d'exécuter directement les instructions SQL.
## Documentations et ressources

* Site officiel de l’app : <http://www.phpmyadmin.net>
* Documentation officielle de l’admin : <https://www.phpmyadmin.net/docs/>
* Dépôt de code officiel de l’app : <https://github.com/phpmyadmin/phpmyadmin>
* YunoHost Store: <https://apps.yunohost.org/app/phpmyadmin>
* Signaler un bug : <https://github.com/YunoHost-Apps/phpmyadmin_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phpmyadmin_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpmyadmin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phpmyadmin -u https://github.com/YunoHost-Apps/phpmyadmin_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>