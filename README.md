# Mumble Web for YunoHost

[![Integration level](https://dash.yunohost.org/integration/bibliogram.svg)](https://dash.yunohost.org/appci/app/bibliogram) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.maintain.svg)  
[![Install Mumble Web with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=bibliogram)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mumble Web quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview


**Shipped version:** 1.0.0

## Screenshots

![](sources/bibliogram.jpg)

## Demo

* [Official demo](https://voice.johni0702.de/?address=voice.johni0702.de&port=443/demo)

## Configuration

Bibliogram requires dedicated domain like `bibliogram.domain.tld`.  
You can configure Bibliogram by editing this file `/var/www/bibliogram/config.js` using this the [documentation](https://git.sr.ht/~cadence/bibliogram-docs/tree/master/docs/Configuring.md)

## Documentation

 * Official documentation: https://git.sr.ht/~cadence/bibliogram-docs
 * YunoHost documentation: https://yunohost.org/#/app_mumble-web

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mumble-web%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mumble-web/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mumble-web%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mumble-web/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/mumble-web_ynh/issues
 * Upstream app repository: https://github.com/Johni0702/mumble-web
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mumble-web_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mumble-web_ynh/tree/testing --debug
or
sudo yunohost app upgrade mumble-web -u https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
```
