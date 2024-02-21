
# Windows Driver Submodule for Xiaomi Redmi K20 Pro based on [SurfaceDuo-Drivers](https://github.com/WOA-Project/SurfaceDuo-Drivers/)
## [Here](https://github.com/woa-msmnile/msmnile-Drivers) is the Full Driver Pack.
<!-- ## ⚠ Remember to decompress Raphael-Drivers\components\QC8150\Graphics\qcdxwsaum.7z and put the image file into the Raphael-Drivers\components\QC8150\Graphics\GRAPHICS.SOC_QC8150.XXX_XXX_XXX/. -->
This repository contains driver binary files for Xiaomi Redmi K20 Pro.
All driver binary files form a board support package to be used on Xiaomi Redmi K20 Pro devices to provide hardware support for the Windows operating system.

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

| Feature                | Notes                                               | Status         |
|------------------------|-----------------------------------------------------|----------------|
| Bluetooth              |                                                     | ✅            |
| Wifi                   |                                                     | ✅            |
| UFS                    |                                                     | ✅            |
| Touch                  |                                                     | ✅            |
| GPU                    | May not work on some devices with unofficial panel. | ✅            |
| Battery                |                                                     | ✅            |
| Buttons                |                                                     | ✅            |
| Light Sensor           |                                                     | ❌            |
| Thermal Sensor         |                                                     | ❌            |
| Haptic                 |                                                     | ❌            |
| Cellular Data          | Need to dump modem at every boot                    | ⚠️            |
| Charge                 |                                                     | ❌            |

## Resources

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Please see [LICENSE](LICENSE.md)

## Installing manually

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/woa-msmnile/msmnile-Drivers
```
