# Oncleben31's custom configuration for ender 3 Pro (Creality 4.2.2 board)

This repository is to track and share my customizations of the Marlin Firmware for my Ender 3 Pro 3D printer.

Main features activated:
 - Manual mesh leveling with a 5x5 matrix
 - Manual corner leveling in menu
 - Custom command to reset the mainboard
 - Custom command to shutdown the Pi hosting Octoprint
 - Host commands acitvation for synchronization with octoprint
 - Enable the Binary File Transfer protocol (to be used with [Firmware Updater Octoprint plugin](https://github.com/OctoPrint/OctoPrint-FirmwareUpdater))

 Inspired by videos from @teachingtechYT

# Configurations
Pre-tested Configurations for Marlin Firmware 2.0.9.2

Marlin Firmware is configured using two files:

- `Configuration.h` contains core configuration options like machine geometry.
- `Configuration_adv.h` contains optional settings for advanced and low level features.

For Graphical LCD these files may also be included:

- `_Bootscreen.h` provides the bitmap for a custom Boot Screen.
- `_Statusscreen.h` provides bitmaps to customize the Status Screen.

See the [Configuration page](https://marlinfw.org/docs/configuration/configuration.html) for more information about configuration and individual configuration options.
