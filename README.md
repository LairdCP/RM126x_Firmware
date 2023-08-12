[![Laird Connectivity](/images/laird_connectivity_logo.jpg)](https://www.lairdconnect.com/)

# RM126x Firmware

[![RM1261 & RM1262](/images/rm126x_render.jpg)](https://www.lairdconnect.com/wireless-modules/lorawan-modules-solutions/rm126x-ultra-low-power-lorawan-a-b-c-module)
[![Silabs](/images/silabs_logo.jpg)](https://www.silabs.com)
[![Semtech](/images/semtech_logo.jpg)](https://www.semtech.com)
[![Gecko SDK](/images/gecko_sdk_logo.jpg)](https://www.silabs.com/developers/gecko-software-development-kit)
[![Simplicity Studio](/images/simplicity_studio_logo.jpg)](https://www.silabs.com/developers/simplicity-studio)

This is the firmware release page for the Laird Connectivity [RM126x][RM126x product brief] product family.

The product is available in [RM1261][RM126x module datasheet] & [RM1262][RM126x module datasheet] variants.

The RM1261 incorporates a [Semtech SX1261][Semtech SX1261 product page] LoRa radio and is intended for use in countries with a transmit power limitation of up to 15dBm (EU, India, Japan, Taiwan & UK).

The RM1262 incorporates a [Semtech SX1262][Semtech SX1262 product page] LoRa radio and is intended for use in countries with a transmit power limitation of up to 22dBm (Australia, New Zealand & US/Canada).

---
**_Note:_** The latest available firmware releases are available on the [RM126x Releases Page].

Details for flashing the different image types can be found in the [Firmware options and upgrade guide] application note.

---

# Content

All firmware is offered in RM1261 and RM1262 versions, depending upon the RM126x variant in use.

## AT Interface

The [RM126x AT Interface][RM126x AT Interface guide] application builds upon many years of AT Interface experience gained with Laird Connectivity's BL65x range of Bluetooth modules. It greatly simplifies integration of a Semtech LoRa radio and stack within a host product, and includes a proprietary Peer to Peer mode for use where LoRaWAN infrastucture is unavailable.

Please refer to the [RM126x AT Interface release notes][RM126x AT Interface release notes] for details of the latest firmware release.

Binaries are available for transfer using the UART bootloader.

## Bootloader

Further details of usage of the bootloader can be found in the [Firmware options and upgrade guide][Firmware options and upgrade guide].

## Factory Image

The Factory Image can be flashed to a module to restore it to the factory state. Note that erasing the device will result in loss of any settings. These should be stored for restoration following erasing of the module followed by flashing of the Factory Image.

[RM126x product brief]: <https://www.lairdconnect.com/documentation/product-brief-rm126x-series>
[RM126x module datasheet]: <https://www.lairdconnect.com/documentation/datasheet-rm126x-lorawan-module>
[RM126x AT Interface guide]: <https://www.lairdconnect.com/documentation/user-guide-rm126x-at-interface-application>
[RM126x AT Interface release notes]: <https://www.lairdconnect.com/documentation/release-notes-rm126x-series>
[RM126x DVK user guide]: <https://www.lairdconnect.com/documentation/user-guide-rm126x-development-kit>
[Native C development guide]: <https://www.lairdconnect.com/documentation/user-guide-lyra-series-c-code-development>
[Firmware options and upgrade guide]: <https://www.lairdconnect.com/documentation/user-guide-firmware-options-and-upgrading-lyra-series>
[RM126x Releases Page]: <https://github.com/LairdCP/RM126x_Firmware/releases/tag/GA1>
[Semtech SX1261 product page]: <https://www.semtech.com/products/wireless-rf/lora-connect/sx1261>
[Semtech SX1262 product page]: <https://www.semtech.com/products/wireless-rf/lora-connect/sx1262>
