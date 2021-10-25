## License:
This project is licensed under the [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).

## Description:

A Magisk module designed to freeze the automated EFS refresh that happens on each reboot. This will enable modifying files normally overwritten by that process.

Currently, this module is designed only for OnePlus devices running OxygenOS 11.

## Disclaimer:

You may very well cause your modem to crash when using this module.
Enable ADB USB Debugging prior to installing, so that you can disable it by removing the module's directory under /data/adb during startup if the modem crashes.
This hasn't been widely tested. Please submit an issue and let me know if this has worked, or not worked for you.
I am not responsible for any damage done to your device, use at your own risk.

## Files replaced:
```
/vendor/bin/rmt_storage
```
