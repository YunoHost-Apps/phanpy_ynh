<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Phanpy for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Working status](https://apps.yunohost.org/badge/state/phanpy)
![Maintenance status](https://apps.yunohost.org/badge/maintained/phanpy)

[![Install Phanpy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Phanpy quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

**Phanpy** is an alternative frontend for Mastodon or Gotosocial servers which are alternatives to X (twitter).

This YunoHost app is built from upstream Phanpy `production` branch.

### Differences from source

built with custom `.env`

* remove references to `phanpy.social` website
* change app name to «Phanpy for YunoHost»
* custom Privacy Policy ([in this repo](https://github.com/YunoHost-Apps/phanpy_ynh/blob/master/PRIVACY.md))
* default language *null* (browser's default)

### Features

* 👪 Multiple accounts
* 🪟 Compose window pop-out/in
* 🌗 Light/dark/auto theme
* 🔔 Grouped notifications
* 🪺 Nested comments thread
* 📬 Unsent draft recovery
* 🎠 Boosts Carousel™️
* ⚡ Shortcuts™️ with view modes like multi-column or tab bar
* #️⃣ Multi-hashtag timeline

from <https://github.com/cheeaun/phanpy#features>

### Third-party services

Inline (and live) translation feature connects to <https://lingva.phanpy.social>. It's optional for the **user** to activate this feature.

## YNH Forum

Comment *phanpy_ynh* on [YunoHost Forum Topic](https://forum.yunohost.org/t/phanpy-a-minimalistic-opinionated-fediverse-web-client/32095)



**Shipped version:** 20250126~ynh1

**Demo:** <https://phanpy.social/>
## Documentation and resources

- Official app website: <https://phanpy.social/>
- Upstream app code repository: <https://github.com/cheeaun/phanpy>
- YunoHost Store: <https://apps.yunohost.org/app/phanpy>
- Report a bug: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
or
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
