---
layout: plugin

id: BetterKlipper
title: BetterOctoKlipper
description: A plugin for a better integration of Klipper into OctoPrint.
author: Evan D (Lbibass)
license: AGPLv3

date: 2020-04-17

homepage: https://github.com/lbibass/OctoprintKlipperPlugin
source: https://github.com/lbibass/OctoprintKlipperPlugin
archive: https://github.com/lbibass/OctoprintKlipperPlugin/archive/master.zip

follow_dependency_links: false

tags:
- klipper
- firmware
- control
- monitor
- updated

screenshots:
- url: /assets/img/plugins/BetterKlipper/log.png
  alt: Main Tab and Message Log
  caption: Main Tab and Message Log
- url: /assets/img/plugins/BetterKlipper/settings.png
  alt: Plugin Settings
  caption: Plugin Settings
- url: /assets/img/plugins/BetterKlipper/config.png
  alt: Klipper Configuratin
  caption: Klipper Configuration
- url: /assets/img/plugins/BetterKlipper/performance.png
  alt: Performance Graph
  caption: Performance Graph
  
featuredimage: /assets/img/plugins/BetterKlipper/log.png

compatibility:

  octoprint:
  - 1.3.8

---

OctoKlipper assists in configuring, controlling and monitoring the [Klipper](https://github.com/KevinOConnor/klipper) 3D-printer firmware.

It provides the following functions:

- Simplified connection dialog.
- Buttons for restarting Klippers host and MCU processes.
- User definable macro buttons that let you execute custom GCODE and Klipper commands.
- An assisted bed leveling wizard with user definable probe points to simplify manual bed leveling.
- A dialog for Klippers PID Tuning.
- A dialog to set a coordinate offset for future GCODE move commands.
- A log displaying only Klipper messages.
- A basic configuration editor to configure Klipper directly through your browser. 
- A performance graph displaying key parameters extracted from the Klipper logs, helpful when debugging performance issues.
- A more theme-friendly css format. 
#### Get Help
If you experience issues with this plugin please use the issue tracker at the plugins github linked on the right.
