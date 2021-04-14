Model device configuration for Unihertz Atom L (Atom_L)
=================================================
This model device tree is intended for the usage in a LineageOS or similar building environment.

If you are looking for a special device tree for the usage in a TWRP or similar environment head over to https://github.com/ADeadTrousers/twrp_device_Unihertz_Atom_LXL.

The Unihertz Atom L (codenamed simply _"Atom_L"_) is a rugged small smartphone from Unihertz, released in July 2020. It is similar to the Atom XL but without an integrated digital mobile radio (DMR).

![](docs/images/atom_l.png)

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Helio P60                                                                                                             |
| GPU                     | Mali-G72 MP3                                                                                                                   |
| Memory                  | 6 GB RAM                                                                                                                       |
| Shipped Android Version | 10                                                                                                                             |
| Storage                 | 128 GB                                                                                                                         |
| Battery                 | Non-removable Li-Po 4300 mAh battery                                                                                           |
| Display                 | 1136 x 640 pixels, ~16:9 ratio (~300 ppi density)                                                                              |
| Camera (Rear - Main)    | 48MP                                                                                                                           |
| Camera (Front)          | 8MP                                                                                                                            |

# Dependencies

Additionally to this model device tree, you'll need the common device tree

- [Atom LXL](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL)

and one or both region device trees

- [Atom L Region EEA (european union)](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_L_EEA)
- [Atom L Region TEE (non-european union)](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_L_TEE)

## Releases

For the actual releases head on over to the device tree of the individual devices:
- [Atom L Region EEA (european union)](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_L_EEA/releases)
- [Atom L Region TEE (non-european union)](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_L_TEE/releases)

## Documentations

- [HOW-TO-BUILD.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-BUILD.md) - Building instructions for LineageOS 17.1.
- [HOW-TO-INSTALL.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-INSTALL.md) - Installation instructions for the Atom L/XL.
- [HOW-TO-UPDATE.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-UPDATE.md) - Update instructions for the Atom L/XL.
- [HOW-TO-EXTRACT_FILES.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-EXTRACT_FILES.md) - Instructions to extract files directly from the Atom L/XL stock rom files.
- [HOW-TO-EXTRACT_SEPOLICY.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-EXTRACT_SEPOLICY.md) - A little guide to extract sepolicy rules from stock or phone.
- [HOW-TO-FLASH-STOCK.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-FLASH-STOCK.md) - Instructions on how to use the SP Flash Tool for MTK based devices.
- [HOW-TO-FLASH-SUPER.md](https://github.com/ADeadTrousers/android_device_Unihertz_Atom_LXL/blob/master/docs/HOW-TO-FLASH-SUPER.md) - Instructions on how to modify super.img and flashing it onto the device.

## Special Thanks To

- [PeterCxy from the XDA forum](https://forum.xda-developers.com/member.php?u=5351691) for helping me and providing the device tree for Atom L.
- [The device tree for the Atom L](https://cgit.typeblog.net/android/device/unihertz/Atom_L/) which was a great step-by-step guide on how to setup my own device tree.
