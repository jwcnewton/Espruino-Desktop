# Espruino Desktop

[![Join the chat at https://gitter.im/espruino/Espruino](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/espruino/Espruino?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
======================

[![ScreenShot](https://raw.github.com/espruino/EspruinoWebIDE/gh-pages/extras/screenshot.png)](http://youtu.be/Fjju_QhzL-c)
[![ScreenShot](https://raw.github.com/espruino/EspruinoWebIDE/gh-pages/extras/screenshot2.png)](http://youtu.be/Fjju_QhzL-c)

It implements basic VT100 terminal features (up/down/left/right/etc) - enough for you to write code using the Espruino. You can also use the right-hand pane to write JavaScript code on the PC, and can then click the 'transfer' icon to send that code directly down the Serial Port.

| Version | Communications | Benefits |
|---------|----------------|----------|
| [Chrome Web App](#installing-from-chrome-web-store) | USB, Serial, [Audio](http://www.espruino.com/Headphone), TCP/IP | Easy to install from [Chrome Web Store](https://chrome.google.com/webstore/detail/espruino-serial-terminal/bleoifhkdalbjfbobjackfdifdneehpo) |
| [Node.js App](#installing-from-npm) / NW.js app | USB, Serial, Bluetooth Low Energy | Can be run of systems without Chrome web browser |
| [Web Version](#full-web-version) | [Audio](http://www.espruino.com/Headphone), Bluetooth Low Energy (via [Web Bluetooth](https://webbluetoothcg.github.io/web-bluetooth/)) | Just go to [a URL](https://espruino.github.io/EspruinoWebIDE/) |

## Support the creators 

The Espruino Web IDE (and Espruino in general) is supported by generous 
donations from many supporters on <a href="https://www.patreon.com/espruino" target="_blank">Patreon</a>

Supporters that pay $10/month or more to help support Espruino are:

Matt Eckman, Michael Leibman, Orry S, Eric Betts, MaBe, Sacha Gloor, INT3GRATION, James Palmer, Andreas Dröscher, 
Erlend Finvåg, Dimitri Deniusov, John Kovach, Spence Konde

## This project seems quiet?

I started this in an airport and I will probably "finish" this in an airport, one of the issues is having the variety of hardware flashed with espruino to hand I currently only have a node mcu and redbear duo flashed!

## Found a bug?

Raise an issue and tag it as bug with steps to reproduce

## Goals/Milestones

- [ ] Finish developement to provide a like for like with functionality in the web IDE
- [ ] Install esptool from desktop
- [ ] Flash espruino from the desktop app, including installing virtual COM Port (VCP) drivers
- [ ] Integrated VS Code ide

## Resources 
[Espruino](http://www.espruino.com/)

[Esptools](https://github.com/espressif/esptool)

[VCP Drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

[Support the creators](https://www.patreon.com/espruino)
