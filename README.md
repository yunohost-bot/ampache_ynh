<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Ampache for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ampache.svg)](https://dash.yunohost.org/appci/app/ampache) ![Working status](https://ci-apps.yunohost.org/ci/badges/ampache.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/ampache.maintain.svg)

[![Install Ampache with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ampache)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Ampache quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Ampache is a web based audio/video streaming application and file manager allowing you to access your music & videos from anywhere, using almost any internet enabled device.

### Features

 * Config for high quality streaming with high bandwith
 * Quick loading for mobile devices with potential low bandwith
 * Integrate with YunoHost users - same username and password
 * Allow one user to be the administrator (set at the installation)

**Shipped version:** 6.2.1~ynh1

**Demo:** https://ampache.org/demo.html

## Screenshots

![Screenshot of Ampache](./doc/screenshots/visualizer.png)

## Documentation and resources

* Official app website: <http://ampache.org>
* Official admin documentation: <https://github.com/ampache/ampache/wiki>
* Upstream app code repository: <https://github.com/ampache/ampache>
* YunoHost Store: <https://apps.yunohost.org/app/ampache>
* Report a bug: <https://github.com/YunoHost-Apps/ampache_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ampache_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ampache_ynh/tree/testing --debug
or
sudo yunohost app upgrade ampache -u https://github.com/YunoHost-Apps/ampache_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>