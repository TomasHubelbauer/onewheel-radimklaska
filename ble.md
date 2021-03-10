---
title: BLE
subtitle: Information able the BLE protocol used by the Onewheel app to communicate with the board.
layout: page
show_sidebar: false
---

# BLE (Bluetooth Low Energy)

Onewheel uses the BLE technology to facilitate communication between the mobile application and the board.

There are several alternative applications to use with the Onewheel:

- [OWCE (Onewheel Community Edition)](https://github.com/OnewheelCommunityEdition/OWCE_App) (iOS and Android)
- [pOnewheel](https://github.com/ponewheel/android-ponewheel) (Android)
- [Onewave](https://github.com/Nanoux/Onewave) (Android)
- [Float Deck](https://apps.apple.com/us/app/float-deck/id1332503706) (iOS, not open source)

Not all of these applications will work with all firmware revisions, because Future Motion has increasingly
locked down and protected the handshake portion of the communication protocol.  OWCE seems to have the best
support for the unlocking.

Here's a few other experimental projects:

- [UWP Onewheel](https://github.com/COM8/UWP-Onewheel) (UWP = desktop support)
- [Onewheel Bluetooth](https://github.com/kariudo/onewheel-bluetooth) (Python unlock implementation)
- [Onewheel Web](https://github.com/drewbaumann/onewheel-web) (OG WebBluetooth unlock implementation)
- [Onewheel WebBluetooth](https://github.com/TomasHubelbauer/onewheel-web-bluetooth) (updated WebBluetooth unlock implementation, but still without support for the latest firmware)
