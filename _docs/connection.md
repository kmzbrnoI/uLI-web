---
title: Connection Setup
permalink: /docs/connection/
redirect_from: /docs/index.html
---

This page describes how to connect uLI to PC and XpressNET.

## uLI–XpressNET connection

Connect uLI to your command station via XpressNET.

Use standard 4-wire or 6-wire direct cable with RJ12 connectors going directly
from a command station or from any XpressNET hub connected to the command
station. Use the same cable as e.g. Roco multiMaus requires.

uLI contains two XpressNET RJ12 connectors which are mutually connected. It does not
matter which connector of uLI you use.

## uLI–PC connection

Use plain USB A-B cable. In some operating systems, driver will install
automatically. If not, you may either download our [pre-extracted
driver](https://github.com/kmzbrnoI/uLI-fw/tree/master/driver_win) or install
*CDC* driver from official [Microchip Libraries for Applications
](http://www.microchip.com/mplab/microchip-libraries-for-applications).

When uLI initializes communication with the PC, green LED marked "DATA" turns off.

## Application configuration

Find out which serial port (e.g. COM4) was assigned to uLI (e.g. via Device Manager on Windows).

Open your railroad-control software and select:

 * **Interface**: Lenz LI100F or Lenz LI101
 * **Port**: uLI's COM port
 * **Baud rate**: any (not important)
 * **Flow Control**: **no flow control** (important!)

### Example: JMRI

<img src="/img/jmri-preferences-hl.png" />
