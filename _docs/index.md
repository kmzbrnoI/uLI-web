---
title: Documentation
permalink: /docs/
redirect_from: /docs/index.html
---

## First Setup

When first obtained uLI, you should remember to setup it correctly.

 1. **Connect uLI to the PC.**

    Use simple USB A-B cable. On some operating systems, driver will install
    automatically. If not, you may either download our [pre-extracted
    driver](https://github.com/kmzbrnoI/uLI-fw/tree/master/driver_win) or install
    *CDC* driver from official [Microchip Libraries for Applications
    ](http://www.microchip.com/mplab/microchip-libraries-for-applications).

    When uLI initializes communication with PC, one of the green LEDs should
    turn off.

 2. **Connect uLI to the XpressNET.**

    Use standard 4-wire or 6-wire direct cable from command station or any
    XpressNET hub connected to the command station. This is the same cable as
    for example Roco multiMaus uses.

    uLI has two XpressNET connectors mutually connected, so you may use uLI
    as an XpressNET hub.

 3. **Connect uLI to an application**

    Use serial port device assigned to uLI. \\
    **Important:** use
     * **any** baud rate and
     * **no flow control**.

## Sources

 * PCB design is available in this repository: \\
   [https://github.com/kmzbrnoI/uLI-pcb](https://github.com/kmzbrnoI/uLI-pcb)

 * Source code of firmware is available in this repository: \\
   [https://github.com/kmzbrnoI/uLI-fw](https://github.com/kmzbrnoI/uLI-fw)

Please see [README](https://github.com/kmzbrnoI/uLI-fw/blob/master/README.md)
file for technical details.

## Contribution

Found a bug? Want to submit a new feature? Submit an
[issue](https://github.com/kmzbrnoI/uLI-fw/issues) or open a
[pull request](https://github.com/kmzbrnoI/uLI-fw/pulls) on GitHub.

Or you may simply write an e-mail to the maintainer:

 * Jan Horacek: [jan.horacek@kmz-brno.cz](mailot:jan.horacek@kmz-brno.cz)

<img src="/img/uLI-open.jpg" alt="" class="img-responsive">
