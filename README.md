# Time Stick

Time Stick is a family of USB Ethernet adapters for precision timing. The hardware timestamps Precision Time Protocol (PTP) packets as they enter and leave the Ethernet port. With Time Stick V3 and the ISPCS app, you can run a PTP exchange and see the measured clock offset and network path delay.

[Time Stick V3 getting started guide](TimeStick3/README.md)

| [Time Stick V1](TimeStick1/) | [Time Stick V2](TimeStick2/) | [Time Stick V3](TimeStick3/) |
| :---: | :---: | :---: |
| [![V1 board with a USB-A plug and gold SMA connector](TimeStick1/images/time-stick-v1-close-up.jpg)](TimeStick1/images/time-stick-v1-close-up.jpg) | [![V2 board marked TIME STICK 2 with a USB-A plug](TimeStick2/images/time-stick-v2-close-up.jpg)](TimeStick2/images/time-stick-v2-close-up.jpg) | [![V3 board with a USB-C plug on the left and Ethernet jack on the right](TimeStick3/images/time-stick-v3-close-up.jpg)](TimeStick3/images/time-stick-v3-close-up.jpg) |

<a href="https://apps.apple.com/app/ispcs/id6803257596"><img src="assets/app-store-badge.svg" alt="Download ISPCS on the App Store" height="40" align="middle"></a>
<a href="https://play.google.com/store/apps/details?id=org.ispcs.conference"><img src="assets/google-play-badge.png" alt="Get ISPCS on Google Play" height="60" align="middle"></a>

## Hardware generations

| Generation | Timing features | Resources |
| --- | --- | --- |
| **Time Stick V3** | USB-C timing adapter. Use ISPCS to operate a grandmaster or follower and inspect PTP measurements. | [V3 setup and first measurement](TimeStick3/README.md) |
| **Time Stick V2** | Adds a pulse-per-second (PPS) input and support for a GNSS receiver. | [V2 overview and hardware files](TimeStick2/) · [Linux driver instructions](TimeStick2/DRV/Readme.txt) · [Order V2](https://www.tindie.com/products/timeappliances/time-stick-v2/) |
| **Time Stick V1** | Gigabit Ethernet with hardware timestamps and a PPS output on an SMA connector. | [V1 overview and schematic](TimeStick1/) · [Linux driver instructions](TimeStick1/DRV/Readme.txt) |

## License

See [LICENSE.txt](LICENSE.txt) for the project's Creative Commons Attribution-NonCommercial 4.0 International license. App Store and Google Play badges are trademarks of their respective owners.
