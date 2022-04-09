<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Ampache for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ampache.svg)](https://dash.yunohost.org/appci/app/ampache) ![](https://ci-apps.yunohost.org/ci/badges/ampache.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ampache.maintain.svg)  
[![Install Ampache with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ampache)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Ampache quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

[Ampache](http://ampache.org) for the love of music. A web based audio/video streaming application and file manager allowing you to access your music & videos from anywhere, using almost any internet enabled device.

###features

 * Config for high quality streaming with high bandwith
 * Quick loading for mobile devices with potential low bandwith
 * Integrate with YunoHost users - same username and password
 * Allow one user to be the administrator (set at the installation)

**Shipped version:** 5.2.1~ynh1

**Demo:** https://ampache.org/demo.html

## Screenshots

![](./doc/screenshots/visualizer.png)

## Disclaimers / important information

## Limitations

* Also, the SSO authentication not fully working from user panel, we have to work about this. In fact, it can disrupt external Ampache clients like Subsonic.

## Additionnal informations

### Getting started

 * **Add your first catalog to load music files**
   * Go to *Admin panel* ![](https://raw.githubusercontent.com/ampache/ampache/develop/themes/reborn/images/icons/icon_admin.png)
   * Click on *Add a Catalog*
   * Fill up fields and click *Add Calalog*
   * Next, enjoy :)

 * **Update a catalog for load new music files**
   * Go to *Admin panel* ![](https://raw.githubusercontent.com/ampache/ampache/develop/themes/reborn/images/icons/icon_admin.png)
   * Click on *Show Catalogs*
   * Select *Update* in *Actions* list and click *Go*

 * **Change interface Language**
   * Go to *Preferences panel* ![](https://raw.githubusercontent.com/ampache/ampache/develop/themes/reborn/images/icons/icon_edit.png)
   * Click on *Interface*
   * Change *Language* field

### Ampache on mobile devices

 * [For Android](https://play.google.com/store/apps/details?id=com.antoniotari.reactiveampacheapp)
 * [For iOS](http://iampache.com/)

 * Full list of existings clients : https://github.com/ampache/ampache/wiki/Clients

## Documentation and resources

* Official app website: http://ampache.org
* Official admin documentation:  https://github.com/ampache/ampache/wiki
* Upstream app code repository: https://github.com/ampache/ampache
* YunoHost documentation for this app: https://yunohost.org/app_ampache
* Report a bug: https://github.com/YunoHost-Apps/ampache_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ampache_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ampache_ynh/tree/testing --debug
or
sudo yunohost app upgrade ampache -u https://github.com/YunoHost-Apps/ampache_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps