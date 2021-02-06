# Adminer pour YunoHost


[![Integration level](https://dash.yunohost.org/integration/adminer.svg)](https://dash.yunohost.org/appci/app/adminer) ![](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)  
[![Installer Adminer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=adminer)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Adminer rapidement et simplement sur un serveur YunoHost.  

Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Adminer (anciennement phpMinAdmin, meilleure alternative à phpMyAdmin) est un outil de gestion de base de données (MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, SimpleDB, Elasticsearch, MongoDB). Remplacez phpMyAdmin par Adminer et vous obtiendrez une interface utilisateur plus ordonnée, une meilleure prise en charge des fonctionnalités MySQL, des performances plus élevées et plus de sécurité. [Voir comparaison détaillée](https://www.adminer.org/en/phpmyadmin).


**Version incluse :** 4.7.8


## Captures d'écran

![](https://www.adminer.org/static/screenshots/db.png)

## Démo

* [Démo officielle](https://demo.adminer.org/adminer.php?username=)

## Configuration

Vous devez connaître le mot de passe root à partir d'ici `/etc/yunohost/mysql` ou le nom d'utilisateur et le mot de passe de l'application dans `setting.yml` sous `/etc/yunohost/apps/appname` pour vous connecter.
Pour les thèmes, téléchargez le fichier adminer.css depuis le site Web principal et placez le fichier dans le dossier de l'application.
Si vous rencontrez des problèmes avec les pilotes, consultez : https://www.adminer.org/en/drivers.

## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/adminer_%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/adminer/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/adminer_%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/adminer/)

## Limitations

* Limitations connues.

## Additional information

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/adminer_ynh/issues
 * Site de l'application : https://www.adminer.org/
 * Dépôt de l'application principale : https://github.com/vrana/adminer/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
or
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```
