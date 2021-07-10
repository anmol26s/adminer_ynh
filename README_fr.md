# Adminer pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/adminer.svg)](https://dash.yunohost.org/appci/app/adminer) ![](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)  
[![Installer Adminer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Adminer rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Gestionnaire de base de données en un seul fichier PHP

**Version incluse :** 4.8.1~ynh1

**Démo :** https://demo.adminer.org/adminer.php?username=

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Vous devez connaître le mot de passe root à partir d'ici `/etc/yunohost/mysql` ou le nom d'utilisateur et le mot de passe de l'application dans `setting.yml` sous `/etc/yunohost/apps/appname` pour vous connecter.
Pour les thèmes, téléchargez le fichier `adminer.css` depuis le site Web principal et placez le fichier dans le dossier de l'application.
Si vous rencontrez des problèmes avec les pilotes, consultez : https://www.adminer.org/en/drivers.

## Documentations et ressources

* Site officiel de l'app : https://www.adminer.org/
* Dépôt de code officiel de l'app : https://github.com/vrana/adminer/
* Documentation YunoHost pour cette app : https://yunohost.org/app_adminer
* Signaler un bug : https://github.com/YunoHost-Apps/adminer_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
ou
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps