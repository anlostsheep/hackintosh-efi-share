[TOC]

# Desktop PC Of Gigabyte B365

## List Of Device

| CPU          | Intel i5-9500               |
| :----------- | :-------------------------- |
| Matherboard  | Gigabyte B365M Arous Elite  |
| SSD          | WestData SN750 500G         |
| Graphic Card | DataLand Radeon RX5500XT 8G |
| Network Card | FV-T919(BCM94360CD)         |

<img src="./about-this-computer.png" style="zoom:40%;" />

## Key Feature

### CPU Turbo

<img src="./cpu-turbo.png" alt="cpu-turbo" style="zoom:40%;" />



### Native power management

<img src="./native-power-management.png" alt="native-power-management" style="zoom:40%;" />



### IGPU Hardware Acceleration

<img src="./igpu-hardware-acceleration.png" alt="igpu-hardware-acceleration" style="zoom:40%;" />



### EGPU Free Drive

<img src="./egpu-free-drive.png" alt="egpu-free-drive" style="zoom:40%;" />



### WIFI

<img src="./wifi.png" alt="wifi" style="zoom:50%;" />



### Bluetooth

<img src="./bluetooth.png" alt="bluetooth" style="zoom:50%;" />



### Airdrop

<img src="./airdrop.png" alt="airdrop" style="zoom:40%;" />

## Others Features

- [x] Sleep and wake up

  > I used `SSDT-GRPW.aml` to fix the wake up from sleep problem, it will shield the wakeup signal of keyboard and mouse, so you have to press the power button to wake up your hackintosh.
  >
  > If you don't like that, just disabled the `EFI/OC/ACPI/SSDT-GPRW.aml` and disabled the `Patch`, like this:
  >
  > <img src="./ssdt-gprw.png" alt="ssdt-gprw" style="zoom:50%;" />

- [x] AppleWatch unlock the screen

- [ ] Istat does't have the GPU RX5500XT temperature

- [x] 

## EFI Guide

### [Opencore 0.7.2 RELEASE](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.2)

- > The best bootloader of the hackintosh at present!



### [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

- > The most complete opencore install guide!



### [黑果小兵的部落阁](https://blog.daliansky.net/)

- > It's a very famous hackintosh tutorial website in china!



### [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

- > I clean up the `Platforminfo` in the `EFI/OC/config.plist`, so you should generate your own `SMBIOS` info and copy-paste them into `EFI/OC/cofnig.plist`, like this : <img src="./platforminfo.png" style="zoom:40%;"/>

