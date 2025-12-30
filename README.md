# TimeStick

## USB to Ethernet with Hardware Timestamping and PPS outoput
A USB 3.2 Gen1 to Gigabit Ethernet dongle based on the AX88179B. 
- The AX88179B supports Precision Time Protocol (PTP) (IEEE 1588v2 and 802.1AS)
- This hardware implementation features a female SMA to break out the 1PPS signal from the AX88179B.

![PHOTO-2024-03-19-19-13-36](https://github.com/opencomputeproject/Time-Appliance-Project/assets/1751211/bad0fec2-05ab-4fcc-91c1-67a0ec44fbe9)

## Order

Order your TimeStick from this link: https://www.tindie.com/products/timeappliances/time-stick-v2/

# Installation

Step 1: First you need to compile the Time Stick module (driver). Either clone the entire repo and take it from there (skip to step 2) so use the following commands:
```
cd
git clone https://github.com/Time-Appliances-Project/TimeStick.git
cd TimeStick/DRV
make
sudo make install
```
Step 2: You need to remove cdc_ncm before installing the AX88179A module.
Please follow the steps below to remove cdc_ncm and install the AX88179A module.

```
sudo rmmod cdc_mbim
sudo rmmod cdc_ncm
sudo rmmod ax88179_178a
```

Step 3: Insert the new module
```
sudo modprobe ax_usb_nic
```

---

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

You are free to:

Share — copy and redistribute the material in any medium or format
Adapt — remix, transform, and build upon the material
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
NonCommercial — You may not use the material for commercial purposes.
For full details, see: https://creativecommons.org/licenses/by-nc/4.0/

As the project creator, I reserve the right to use this material commercially or under any other terms.
