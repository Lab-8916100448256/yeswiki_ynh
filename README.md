<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# YesWiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/yeswiki.svg)](https://dash.yunohost.org/appci/app/yeswiki) ![](https://ci-apps.yunohost.org/ci/badges/yeswiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yeswiki.maintain.svg)  
[![Install YesWiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yeswiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install YesWiki quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

YesWiki is a wiki designed to remain simple, very easy to install, in French translated into English, Spanish, Catalan, Flemish...

However, with a YesWiki we can build a website with multiple uses:
- Gather all the information of a project or a group (function of "central station")
- Mapping members or places in a participatory way
- Share resources, lists, calendars thanks to powerful cooperative databases
- Communicate information flows
- Cultivate a bit of freedom...


**Shipped version:** 2022-01-16-13~ynh1

**Demo:** https://ferme.yeswiki.net/?CreerSonWiki

## Screenshots

![](./doc/screenshots/yeswiki_screenshots.png)

## Disclaimers / important information

#### Multi-users support

LDAP integration is supported and required on new installs. It is possible to disable it on older installs by removing the loginldap plugin. **Warning: only do it if you know credentials for a wiki admin account**

At the moment SSO authentication is not supported. It is necessary to login on the wiki.

## Documentation and resources

* Official app website: https://yeswiki.net/
* Official admin documentation: https://yeswiki.net/?DocumentatioN
* Upstream app code repository: https://github.com/YesWiki/yeswiki
* YunoHost documentation for this app: https://yunohost.org/app_yeswiki
* Report a bug: https://github.com/YunoHost-Apps/yeswiki_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/yeswiki_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yeswiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade yeswiki -u https://github.com/YunoHost-Apps/yeswiki_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps