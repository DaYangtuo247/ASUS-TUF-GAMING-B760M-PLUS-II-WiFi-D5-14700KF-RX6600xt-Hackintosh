# macOS on 14700KF B760M PLUS II D5

## Specifications

| Item                 | Info                             |
| -------------------- | -------------------------------- |
| Model                | TUF gaming B760M plus ii WIFI D5 |
| CPU                  | i7-14700KF                       |
| DGPU                 | RX 6950xt                        |
| RAM                  | 2x16GB  DDR5 6400MHz             |
| NVMe                 | WD_BLACK SN850X 1TB              |
| WIFI and Bluetooth   | T919（BMC94360CD）               |
| Ethernet             | RTL8852                          |
| Opencore Version     | 1.0.3                            |
| SMBIOS used          | MacPro7,1                        |
| Target MacOS Version | MacOS 13.6.7                     |

## What's Working

| Item            | Status | Notes                                                        |
| --------------- | ------ | ------------------------------------------------------------ |
| CPU             | ✅      | no problem |
| HDMI A/V out    | ✅      |                                                              |
| USB             | ✅      | All ports working with USBMap.kext                       |
| Keyboard        | ✅      | Voodoops2controller Kext + Karabiner-Elements app for mapping |
| Audio           | ✅      | AppleALC kext working with layout-id 3                       |
| Trackpad        | ✅      | VoodooI2C                                                    |
| Ethernet        | ✅      | RealtekRTL8111 Kext                                          |
| brcm WIFI      | ✅      | need AirportBrcmFixup.Kext                                            |
| Bluetooth       | ✅      | Internal Intel combo card with IntelBluetoothFirmware.kext + BlueToolFixup Kext |
| Battery         | ✅      | SMCProcessor.kext + SMCSuperIO.kext |
| AppleTV+ DRM    | ✅      | Work with CFG_LINK_FIXED_MAP=1                               |
| iServices       | ✅      | Message/Facetime tested and working                          |
| Shutdown/Reboot | ✅      |                                                              |

## What's not Working

* unknow

## BIOS option
* Secure Boot **Disabled**
