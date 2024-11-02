<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Komga for YunoHost

[![Integration level](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![Working status](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)

[![Install Komga with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Komga quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Komga is a free and open source comics/mangas server.

### Features

- Browse libraries, series and books via a responsive web UI that works on desktop, tablets and phones
- Organize your library with collections and read lists
- Edit metadata for your series and books
- Import embedded metadata automatically
- Webreader with multiple reading modes
- Manage multiple users, with per-library access control
- Offers a REST API, many community tools and scripts can interact with Komga
- Download book files


**Shipped version:** 1.12.1~ynh2

**Demo:** <https://demo.komga.org>

## Screenshots

![Screenshot of Komga](./doc/screenshots/home.png)

## Documentation and resources

- Official app website: <https://komga.org>
- Official admin documentation: <https://komga.org/guides/>
- Upstream app code repository: <https://github.com/gotson/komga>
- YunoHost Store: <https://apps.yunohost.org/app/komga>
- Report a bug: <https://github.com/YunoHost-Apps/komga_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
or
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
