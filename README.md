<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Ecko for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ecko.svg)](https://dash.yunohost.org/appci/app/ecko) ![](https://ci-apps.yunohost.org/ci/badges/ecko.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ecko.maintain.svg)  
[![Install Ecko with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ecko)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Ecko quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Dynamic fork of Mastodon's federated social network, est. Aug 2021.

**Shipped version:** 2021-11-20~ynh1

## Disclaimers / important information

Ecko is beta software, and under active development. Use at your own risk!

* This app require a dedicated domain or subdomain.
* The user choosen during the installation is created in Ecko with admin rights.
* LDAP authentication is activated. All YunoHost users can authenticate.
* Single sign-on doesn't work.

You may wish to close or limit registration for your instance of Ecko, so that the instance stays small. We invite you to block remote malicious instances from the administration interface. You can also add text on your home page.

## Documentation and resources

* Official app website: https://magicstone.dev
* Upstream app code repository: https://github.com/magicstone-dev/ecko
* YunoHost documentation for this app: https://yunohost.org/app_ecko
* Report a bug: https://github.com/YunoHost-Apps/ecko_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ecko_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ecko_ynh/tree/testing --debug
or
sudo yunohost app upgrade ecko -u https://github.com/YunoHost-Apps/ecko_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps