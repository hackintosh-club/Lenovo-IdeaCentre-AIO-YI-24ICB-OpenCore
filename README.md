# IdeaCentre-AIO-YI-24ICB Hackintosh OpenCore EFI

![image](ScreenShot/AIOYI24ICB.png)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.9.2](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 

### Hardware

- Motherboard:Lenovo 36FB (B360)
- Bios Version: 044CT20A（2021/12/23）
- CPU: Intel i5-8400T
- RAM: SK hynix 8G*2 DDR4 2666MHz
- SSD: 1.TOSHIBA KXG5AZNV256G Windows 10
- SSD: 2.Kimtigo SATA SSD 480G MacOS
- iGPU: Intel UHD Graphics 630
- Audio: Realtek ALC235
- Ethernet: Realtek RTL8111
- Wireless: BCM94360NG (Replace Realtek RTL8821CE ，this card can not use in hackintosh)
- Display: Lenovo LENF9OO LEN-A340C-B-A 23.8 inch


### BIOS

```
Devices
  |-- ATA Drive Setup
    |-- Configure STAT as: ACHI
  |-- Video Setup
    |-- Select Active Video: IGD
    |-- Pre-Allocated Memory Size: 64MB
    |-- Total Graphics Memory: Maximum

Advanced
  |-- CPU Setup
    |-- Intel(R) Hyper-Threading Technology: Enabled
    |-- Core Multi-Processing: Enabled
    |-- Intel(R) Virtualization Technology: Enabled
    |-- VT-d Feature: Disabled

Power
  |-- Automatic Power On
    |-- Wake on LAN: Disabled

Security
  |-- Secure Boot
    |-- Secure Boot: Disabled

Startup
  |-- Fast Boot: Disabled
```

### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your SMBIOS
 
 - U Must Use CFGLock.efi Tool Unlock CFG LOCK first
 
![image](Screenshot/CFGLock.efi.png)


### Known issues

- `WiFi` and `Bluetooth` unserviceable with Realtek RTL8821CE .
- `HDMI` Port unserviceable .

 
### ScreenShot 

![macOS Ventura](Screenshot/about.png)

### Contact Us

QQ Group: 23304408

![image](ScreenShot/QRCode.png)

