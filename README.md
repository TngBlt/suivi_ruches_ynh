<!--
N.B.: This README was auto-inspired by Yunohost's app structure.
Replace YOUR-USERNAME below with your GitHub username.
-->

# Suivi Ruches for YunoHost

[![Integration level](https://dash.yunohost.org/integration/suivi_ruches.svg)](https://dash.yunohost.org/appci/app/suivi_ruches)
![Working status](https://ci-apps.yunohost.org/ci/badges/suivi_ruches.status.svg)
![Maintenance status](https://ci-apps.yunohost.org/ci/badges/suivi_ruches.maintain.svg)

[![Install Suivi Ruches with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=suivi_ruches)

*[Lire ce readme en français](./README_fr.md).*

> *This package allows you to install Suivi Ruches quickly and simply on a YunoHost server.*
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Suivi Ruches is a beekeeping monitoring application designed for hobbyist and professional beekeepers practicing gentle beekeeping ("apiculture douce").

### Features

- 🐝 **Hive management**: Track multiple hives with their state, queen, frames, and varroa counts
- 📋 **Frame visualization**: Visual representation of each frame with type and content
- 📝 **Intervention journal**: Detailed log of all hive operations
- 👁️ **Guided observation template**: Structured checklist to never forget important observations
- 🎤 **Voice dictation**: Record observations hands-free using speech-to-text (French)
- 📸 **Photo support**: Multiple photos per intervention with full-screen viewing
- 📦 **Inventory management**: Track frames, equipment, food, and supplies
- 🧠 **Dr. Abeille AI**: AI-powered beekeeping assistant (optional - requires Anthropic API key)
- 🌿 **Flora & Fauna analysis**: Identify melliferous plants and insects
- 📅 **Monthly calendar**: Tasks and risks reminders by season
- ⚠️ **Automated alerts**: Swarming risk, missing queen, varroa overload warnings

**Shipped version:** 1.4.0~ynh1

## Screenshots

<!-- Add screenshots here when available -->

## Documentation and resources

- Upstream app code repository: <https://github.com/TngBlt/suivi-ruches>
- YunoHost Store: <https://apps.yunohost.org/app/suivi_ruches>
- Report a bug: <https://github.com/TngBlt/suivi_ruches_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/TngBlt/suivi_ruches_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/TngBlt/suivi_ruches_ynh/tree/testing --debug
or
sudo yunohost app upgrade suivi_ruches -u https://github.com/TngBlt/suivi_ruches_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
