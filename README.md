# Home Assistant integration for NAD receivers

![Python][python-shield]
[![GitHub Release][releases-shield]][releases]
[![Licence][license-shield]][license]
[![Maintainer][maintainer-shield]][maintainer]
[![Home Assistant][homeassistant-shield]][homeassistant]
[![HACS][hacs-shield]][hacs]  
[![Github Sponsors][github-shield]][github]
[![PayPal][paypal-shield]][paypal]
[![BuyMeCoffee][buymecoffee-shield]][buymecoffee]
[![Patreon][patreon-shield]][patreon]

## Introduction

Home Assistant integration to control NAD receivers over the serial interface or serial
to network bridges like [esp-link](https://github.com/jeelabs/esp-link).

## Features

- Installation/Configuration through Config Flow UI

## Installation

### HACS

The recommended way to install this Home Assistant integration is by using [HACS][hacs].
Click the following button to open the integration directly on the HACS integration page.

[![Install NAD from HACS.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=rrooggiieerr&repository=homeassistant-nad&category=integration)

Or follow these instructions:

- Go to your **HACS** view in Home Assistant and then to **Integrations**
- Open the **Custom repositories** menu
- Add this repository URL to the **Custom repositories** and select
**Integration** as the **Category**
- Click **Add**
- Close the **Custom repositories** menu
- Select **+ Explore & download repositories** and search for *NAD*
- Select **Download**
- Restart Home Assistant

### Manually

- Copy the `custom_components/nad` directory of this repository into the
`config/custom_components/` directory of your Home Assistant installation
- Restart Home Assistant

## Adding a new NAD receiver

- After restarting go to **Settings** then **Devices & Services**
- Select **+ Add integration** and type in *NAD*
- Select the *Serial port* or enter the path manually
- Select **Submit**

When your wiring is right a new NAD receiver integration and device will now
be added to your Integrations view. If your wiring is not right you will get a
*Failed to connect* error message.

## Contribute your language

If you would like to use this Home Assistant integration in your own language you can provide a
translation file as found in the `custom_components/nad/translations` directory. Create a pull
request (preferred) or issue with the file attached.

More on translating custom integrations can be found
[here](https://developers.home-assistant.io/docs/internationalization/custom_integration/).

## Star this repository

Help other Home Assistant users find this integration by starring this repository. Click **⭐ Star**
on the top right of the GitHub page.

## Support my work

Do you enjoy using this Home Assistant integration? Then consider supporting my work using one of
the following platforms, your donation is greatly appreciated and keeps me motivated:

[![Github Sponsors][github-shield]][github]
[![PayPal][paypal-shield]][paypal]
[![BuyMeCoffee][buymecoffee-shield]][buymecoffee]
[![Patreon][patreon-shield]][patreon]

## Hire me

If you would like to have a Home Assistant integration developed for your product or are in need
for a freelance Python developer for your project please contact me, you can find my email address
on [my GitHub profile](https://github.com/rrooggiieerr).

[python-shield]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[releases]: https://github.com/rrooggiieerr/homeassistant-nad/releases
[releases-shield]: https://img.shields.io/github/v/release/rrooggiieerr/homeassistant-nad?style=for-the-badge
[license]: ./LICENSE
[license-shield]: https://img.shields.io/github/license/rrooggiieerr/homeassistant-nad?style=for-the-badge
[maintainer]: https://github.com/rrooggiieerr
[maintainer-shield]: https://img.shields.io/badge/MAINTAINER-%40rrooggiieerr-41BDF5?style=for-the-badge
[homeassistant]: https://www.home-assistant.io/
[homeassistant-shield]: https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white
[hacs]: https://hacs.xyz/
[hacs-shield]: https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge
[paypal]: https://paypal.me/seekingtheedge
[paypal-shield]: https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white
[buymecoffee]: https://www.buymeacoffee.com/rrooggiieerr
[buymecoffee-shield]: https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black
[github]: https://github.com/sponsors/rrooggiieerr
[github-shield]: https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA
[patreon]: https://www.patreon.com/seekingtheedge/creators
[patreon-shield]: https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white
